## Project Target:
At the automobile sector, Comparison of Revenues of two pioneer company which are Tesla and Ford Motors. 
## Required Data for satisfy project target: 
Revenues, stock prices
## Desired Outputs: 
Plots of two figures which are Revenue vs Date and Stock price vs Date for each company.

## Project Phases:
  ##  1) DATA COLLECTION PHASE
  - 1.A) Stock data of Tesla and Ford Motors are extracted from Yahoo Finance with yfinance function 
  - 1.B) Stock data of Tesla and Ford Motors are extracted with webscrapting
  ##  2) DATA PREPERATION PHASE
  - Values at Revenue column have dollar signs and commas instead of dots. Data need to be manipulated for numerical calculations such as finding mean value of Revenue. For this reason dolar sign ("$") is neglected and commas (",") are replaced with dot (".")
  ##  3) DATA VISUALIZATION PHASE
  - Visualization function is created and desired outputs are made. Each figures values which are stock prices and revenues, are dependendent to each other with time parameter. Date can be trimmed with using gui for observe relations between revenue and stock prices in a specific time interval. 
  
   ###  Revenue vs Date and Stock price vs Date for Tesla
  ![output_tesla](https://user-images.githubusercontent.com/114949587/225123090-ebcb98ec-a6f5-4274-9d74-fa14bc237c2c.png)

   ###  Revenue vs Date and Stock price vs Date for Tesla
  ![output_ford_motors](https://user-images.githubusercontent.com/114949587/225124266-5066e616-1e54-41e1-af00-13d0ac6791ae.png)
  


