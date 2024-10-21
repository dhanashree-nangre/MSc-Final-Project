**Comparing the Quality of Fingerprint Images by Two Different Sensors**

**Author:** Dhanashree Nangre (2544403)

**Supervisor:** Oluwafemi Samuel

**Institution:** School of Science and Engineering, University of Dundee, Scotland


**Project Overview**

This project explores the comparative quality of fingerprint images obtained using two different sensor technologies: optical sensors and light-emitting sensors (LES). The focus is on analyzing and assessing the quality of fingerprint images based on datasets MASIVE (light-emitting sensor) and SOCOFing (optical sensor). By leveraging fingerprint quality metrics, this project aims to provide insights into the accuracy and reliability of different sensor technologies in fingerprint recognition systems.


**Objective**

To assess and compare the quality of fingerprint images collected by two different sensors, optical and light-emitting, using the NFIQ2.0 tool. The analysis considers factors such as gender, hand, and finger type, and proposes practical solutions for improving fingerprint image quality.


**Datasets**

MASIVE: A dataset of fingerprint images collected from Nigerian volunteers using a light-emitting sensor.

Sensor Used: Integrated Biometrics’ Columbo 500 PPI single fingerprint scanner

Number of Images: 12,000+

Metadata: Gender, hand, finger type, occupation, physical conditions, environmental factors (e.g., humidity, temperature)

SOCOFing: A publicly available dataset collected using an optical sensor.

Sensor Used: Hamster Plus (HSDU03PTM) and SecuGen SDU03PTM scanner

Number of Images: 6,000

Metadata: Gender, hand, finger type


**Methodology**

Data Collection: Fingerprint images from the MASIVE and SOCOFing datasets were used for this project. MASIVE is an unpublished dataset, while SOCOFing is publicly available on Kaggle.

Image Preparation: The images were prepared for quality assessment using the NFIQ2 tool. SOCOFing images required preprocessing to meet the NFIQ2 standards, including conversion to grayscale and adjusting the PPI.

Quality Assessment: The NFIQ2 tool was used to extract quality scores from the fingerprint images. A script was developed to automate the image processing and quality score extraction.

Data Analysis: Analysis was performed using Python, pandas, and Tableau. Comparative and statistical analyses were conducted to evaluate the image quality across different sensor types, hands, and fingers.


**Key Findings**

Light-emitting sensors capture higher-resolution images, resulting in better quality scores compared to optical sensors.

Left-hand fingerprints generally show higher quality scores than right-hand fingerprints.

Fingerprints of thumbs consistently achieved higher quality scores compared to other fingers.

A higher number of minutiae points does not necessarily correlate with higher image quality.


**Programming Languages**: Python (for data processing and analysis)

**Tools:** NFIQ2, pandas, Tableau

**Data Visualization:** Tableau, Power BI

**Datasets:** MASIVE (Unpublished, University of Dundee), SOCOFing (Publicly available on Kaggle)

