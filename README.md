# Cashew Classification - Undergraduate AI Capstone HW1

## Introduction
This project aims to classify different brands of cashews using **Machine Learning** techniques.  
The dataset consists of cashew measurements (width, length, and weight), and we apply **supervised & unsupervised learning** to classify the cashew brands.

---

## Dataset Description
The dataset (`cashew.xlsx`) contains measurements of cashews from 3 different brands, each with 100 samples(totally 300 samples, none of the sample and feature is missing).  
Each sample has **three numerical features**:

|    Feature   |        Description       | Data Format |
|--------------|--------------------------|-------------|
| `width(mm)`  | Width of the cashew nut  |     int     |
| `height(mm)` | Height of the cashew nut |     int     |
| `weight(mg)` | Weight of the cashew nut |     int     |

The dataset also contains a **target label (`type`)**, indicating the brand of the cashew:

- **Type 1**: 大潤發
- **Type 2**: 盛香珍
- **Type 3**: 臻品行

---

## Data Source 
The cashews of brand 大潤發 and of brand 盛香珍 are bought from 大潤發 with two bags of each brand (150g each bag, and the expiration dates of the same brand are the same).  
The cashews of brand 臻品行 is bought from Shopee with one bag only (300g each bag).  
All of the data here is measured by the owner personally.

## Measurement Description
