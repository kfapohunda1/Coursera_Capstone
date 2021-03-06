# 1. A description of the problem and a discussion of the background.

Low back pain (LBP) is a leading cause of pain and disability. Substance use disorder (SUD) complicates the management of LBP, and potential risks increases with aging. Despite implications for an aging, diverse U.S. population, substance use and LBP comorbidity remain poorly defined. 

The objective of this project is to geographically characterize the distribution of low back pain and substance use disorder using CMS data, Folium library and Foursquare API. By having a visual representation of opioid disorder and low back pain on a map we can then identify clusters and segment patients into these clusters. 

By segmenting and clustering the beneficiaries with these diagnosis, we can help stakeholders (health department) identify the hotspot or regions most affected by LBP and SUD, identify the rate of diagnosis by specific region,  and how to efficiently distribute available resources to make significant impact.

# 2.	A description of the data and how it will be used to solve the problem.

The data needed to address this issue includes CMS data, Foursquare API and folium library for mapping. The CMS data is the federal government data that relates to traditional Medicare Fee-For-Services. It includes over 1,477,594 U.S. Medicare beneficiaries, 37,634,210 claims, and 92,903,649 diagnostic code assignments. However, after performing ETL for beneficiaries who were diagnosed with substance disorder and low back pain, we are able cluster, segment and map them using.

There are numerous insights we can gain by building machine learning models for the CMS data. These includes the proximity of medical centers (hospital, clinics etc.) to highly clustered areas,  the rate of low back pain and opioid diagnosis across a specified region (Baltimore, Maryland), Identification of  conditions that are co-diagnosed with low back pain across different region, Identify the areas that are hotspot or most affected by LBP and SUD, Economic impact of LBP and opioid use across a specified region and Identification of attributes (features) that predict the chances of being diagnosed with LBP and SUD and evaluation of the predictions



