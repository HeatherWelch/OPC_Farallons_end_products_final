# OPC Farallons end products  
Operational predictions of blue whale (probability of presence), humpback (density), anchovy (probability of presence), and EPAC (catch per unit effort, CPUE) distributions. For each species, outputs include:  

## Daily products  
### 1. Rasters  
Daily rasters of predicted distribution (.grd and .gri; "rasters")   
### 2. Maps  
Daily maps of predicted distribution (.png; "maps")   
### 3. EPAC metadata    
Daily metadata (.csv; "epac_metadata") for each EPAC prediction documenting how many days of data were available to make each rolling average monthly prediction in 1. & 2.    

## Two week products    
### 4. Two week rasters  
Rolling two week average rasters (.grd and .gri; "two_week_rasters") of predicted distribution    
### 5. Two week maps  
Rolling two week average maps (.png; "two_week_maps") of predicted distribution    
### 6. Two week metadata  
Rolling two week metadata (.csv; "two_week_metadata") for each output in 4. & 5. documenting how many days of data were available. Metadata can be matched to two week predictions by “end20XX-XX-XX”  

## Indicators  
### 7. RAMP zone indicators  
Daily indicators (.csv and .png; "ramp_zone_indicators") of average predicted distribution in RAMP zones 3 and 4    

# Downloading products 
## If you don't use github: 
A. Navigate to the folder you want to download and copy URL, e.g. raster data for November 2023: https://github.com/HeatherWelch/OPC_Farallons_end_products_final/tree/main/rasters/2023/11  
B. Paste URL in box here: https://download-directory.github.io/  
C. Folder will be compressed and downloaded  

## If you use github:  
A. Clone the repository: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository

## If you use R: 
(And want to integrate products into an operational workflow)

library(RCurl)
library(tidyverse)
library(glue)



