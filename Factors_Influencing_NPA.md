# TOP factors which influence the NPA of a person 
## Personal Detils 
1. Age 
2. Educational status 
3. Marital Status
4. Wealths status (BPL)
5. Years of experiance
6. Type of Farming
7. irrigation facility 
8. Previous Loans (will check if any previous loan is NPA or not)

## Area specification 
1. Land holding of the farmer (small_farmer,medium_farmer,large_farmer)
2. According to agro climatic condition (UNI_irrigated , SEMI_irrigated , FULLY_irrigated)
3. No. of crops in a one crop year (MONO_cropping , DOUBLE_cropping , MULTI_cropping)
4. According to farming (traditional_farming , specialized farming , commercial farming , mixed farming)   **(ToF)**

### Use of **Raster** as Thematic map
Thematic map
A thematic map is used to classify a geographical area. Each zone is associated with a particular class sharing some characteristics. For example, we can classify an agricultural area according to the type of plantations. Rasters are perfect for this task because each cell can store the integer value representing the class to which the pixel associated area belongs.

Below is an example of a thematic map from Lombardia, an Italian region. Each pixel stores a value between 0 and 6 depending on the class:
![theamatic map](https://github.com/moulik13/Project_NPA_NIC/assets/74233936/51010f37-d4e2-4a55-87f4-c63bc8706ab4)

# custom data set 

![customNPA](https://github.com/moulik13/Project_NPA_NIC/assets/74233936/29798ae1-cc01-40e6-b368-a62244824a6d)

there shoud be **Feature** in the table which we will predict 

## Income Expendature analysis
1. Income 
2. spendings
3. profit
4. cost of living at that location 
5. Family size 
6. inflation rate 
