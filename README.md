# Call Analysis Project for Tools For Analytics 
Section: Section 2; Group number: Group 9

Group members: Yuwen Huang(yh3413), Linzi Guan(lg3183)

## Introduction:

In this project, we have done two separate analyses on the "311_Service_Requests_2020.csv" dataset, which is published by New York City government tracking all the calls to the 311 phone number for non-emergency services. With curiosity about the neighbourhood we are living in, we mainly paid our attention to calls related to zip 10025. In the first part, with the interest to investigate what incidents concerned people living nearby most last year, we listed the top 10 types of incidents around complained by people. And as illegal parking has been a large concern for people living in neighbourhoods and with the interest to figure out whether it is a large problem in our neighbouthood, in the second part, we compared the illegal parking complaint rate in our neighbour with the general illegal parking complaint rate in New York City. The introduction describes the data we used first, and then introduces the analyses we conducted and ends with our conclusion.

This repository contains three files: A Readme file to describe our work, a Top10.ipynb with our analysis of top 10 incident types and a Parking.ipynb with our analysis of parking incidents


## Data
Data Set: "311_Service_Requests_2020.csv"
This data set is published by form New York City for public consumption or use. Amongst them is a dataset consisting of calls to the 311 phone number for non-emergency services. The data set consists of 2587316 data points on the created date, close date, agency, agency name, complanit tpye, Descriptor, Location Type and totally 41 others columns. 

## Analyses
For Top10.ipynb:
Through groupby and sort operation, we get top 10 causes of calls to 311 in 10025, associate with the total number of incidents of each type. The first column is the name of each tpyes, and the second column is the total numbers for the corresponding types. 

For Parking.ipynb:
Our answer is in the form of a single bool called named higher_parking_proportion. We get False when higher_parking_proportion is called.
The main idea of the this question is the function groupby().

## Conclusion
We found that top 10 concerns in our neighbourhood in 2020 is as following:
Noise - Residential            2952
Noise - Street/Sidewalk        2128
HEAT/HOT WATER                 1885
Noise                          1131
Illegal Parking                 792
Noise - Vehicle                 787
Non-Emergency Police Matter     773
Rodent                          691
Illegal Fireworks               672
UNSANITARY CONDITION            565
And illegal parking complaint rate in our neighbourhood is lower than the general illegal parking complaint rate in New York City, which shows illegal parking is not a big concern compared to other concerns in our neighbourhood.
