# Mobility and Housing in Taipei
CYPLAN 255, Spring 2024 Final Project <br />
Instructor: Max Gardner / GSI: Meiqing Li 
<br /><br />

## Brief Summary
This project aims to utilize mobility, population, and housing data at different times to study the spatial and temporal aspects of different districts in Taipei City, Taiwan.
The goal of this project is to propose a more seamless, intelligent, and adaptable urban living experience, enhancing convenience and efficiency in city living.

Data Source:
1. [YouBike 2.0 (bike-sharing system) Real-Time Data](https://tcgbusfs.blob.core.windows.net/dotapp/youbike/v2/youbike_immediate.json)
2. [Top 10 most used/busiest YouBike 2.0 stations: December, 2023](https://data.taipei/api/v1/dataset/c7a076dd-8aa6-4129-9c8a-e04cbf18694f?scope=resourceAquire)
3. [Taipei City Population by District: Jan, 2022](https://data.taipei/api/v1/dataset/9681db4c-fb1b-4a23-9013-e74483b6b046?scope=resourceAquire)
4. [Real Estate Pricing in Taipei 2012[Q1-Q4]-2023[Q1-Q4]](https://plvr.land.moi.gov.tw/Index)
5. [Taipei Metro (MRT) Stations Exits](https://data.gov.tw/dataset/128428)

## 1. Bike Sharing System (YouBike 2.0) in Taipei

The availability of bikes differs at different times and locations. Take the National Taiwan University (NTU)/Gongguan area as an example.
During daytime, the supply is high (bottom left image). However, the supply is low during peak hours and times other than daytime (bottom right image).
![CP255_Final_Presentation_Page_02](https://github.com/jcmchen/CYPLAN255_2024_Final_Project/assets/70067477/af4a47f4-8f6c-4995-94b6-fb099529063f)

Heatmaps were intrudoced to visualize the density of bike stations. Given the high density of bike stations in the National Taiwan University (NTU)/Gongguan area
(bottom left image), the supply is still low in the whole area, showing red on the bottom right image.

![CP255_Final_Presentation_Page_03](https://github.com/jcmchen/CYPLAN255_2024_Final_Project/assets/70067477/9bdc701d-99f6-4b72-82e4-2e1d3ed67680)

Based on the historical data (December, 2023), the top 10 most used/busiest stations are all stations located at the exists of the Taipei Metro (MRT) stations.
Those stations are not always busy throughout the whole day. Three stations near National Taiwan University (NTU) has low supply at 8:29 AM due to the university
has its first class starting at 9:10 AM (bottom left image).

![CP255_Final_Presentation_Page_04](https://github.com/jcmchen/CYPLAN255_2024_Final_Project/assets/70067477/8e98ec0f-cb56-40f7-85a1-4f2524b23ab8)

Taipei, the capital city of Taiwan, is divided into 12 administrative districts. These districts are: Zhongzheng, Datong, Zhongshan, Songshan, Daan, 
Wanhua, Xinyi, Shilin, Beitou, Neihu, Nangang, and Wenshan. Based on the population data (Jan, 2022), the figure below shows the number of stations does not align with the number of population.
![CP255_Final_Presentation_Page_05](https://github.com/jcmchen/CYPLAN255_2024_Final_Project/assets/70067477/f3462d6d-3b27-45aa-a2af-e10324d52960)

## 2. Housing Price in Taipei (2012-2023)

88101 housing price information was collected from 2012-2023(Q1-Q4) from the Dept of Land Administration M. O. I., Taiwan.
Among all the districts, Daan district has the highest housing price consistently. Other districts then could be clustered into three pricing levels (dark blue,
light blue, and yellow-orangish).


![CP255_Final_Presentation_Page_06](https://github.com/jcmchen/CYPLAN255_2024_Final_Project/assets/70067477/92930581-6448-484b-af40-cfa4307927f0)

Figures below show the housing price and price distribution by districts.

![CP255_Final_Presentation_Page_07](https://github.com/jcmchen/CYPLAN255_2024_Final_Project/assets/70067477/7b0bff1d-ddf8-4ff1-8faf-772e3aaceff1)

Images below show the price distribution: <br />
(1) between districts with the highest (Daan) and the lowest (Beitou) price. <br />
(2-4) between districts in the same housing price level (dark blue,
light blue, and yellow-orangish).

![CP255_Final_Presentation_Page_08](https://github.com/jcmchen/CYPLAN255_2024_Final_Project/assets/70067477/c15ddbb8-645e-4b59-8579-2f99767bbc96)

When it comes to building types, the price of apartment is relatively lower than other three building types. Also, the correlation analysis from 2012-2023 suggests
that prices tend to retain their value better when they are higher.

![CP255_Final_Presentation_Page_09](https://github.com/jcmchen/CYPLAN255_2024_Final_Project/assets/70067477/ed8f7b75-4096-4dbb-b973-031a0c908b23)

# 3. Housing Price and Taipei Metro (MRT) Stations in Taipei
<br />
2500 housing information in the same year was randomly selected to plot on the map below. <br /><br />

![CP255_Final_Presentation_Page_10](https://github.com/jcmchen/CYPLAN255_2024_Final_Project/assets/70067477/0cf90d7c-42e5-4078-a6aa-4fb17dfcd79e)

<br /><br />
The Taipei Metro (MRT) system primarily serves Taipei City and New Taipei City, which are the two largest cities in northern Taiwan. Stations in Taipei City
were clipped and colored in red. Stations in New Taipei City were colored in yellow (bottom right image).

![CP255_Final_Presentation_Page_11](https://github.com/jcmchen/CYPLAN255_2024_Final_Project/assets/70067477/c1e584a5-4ee7-4cb3-aa15-0b19301a0ae3)

Image below shows the housing location (blue) and MRT exits (red) in Taipei City.<br /><br />
![CP255_Final_Presentation_Page_12](https://github.com/jcmchen/CYPLAN255_2024_Final_Project/assets/70067477/f4fd98ce-c700-496e-9dd5-1afb130613bd)

<br /><br />
Images below show the unfiltered (left) and filtered (right) housing within 5-minute walking distance from MRT exits (isochrones).  

![CP255_Final_Presentation_Page_13](https://github.com/jcmchen/CYPLAN255_2024_Final_Project/assets/70067477/42c83817-b156-49c6-9a4b-5842dd211afc)

Zoom-in view of the exits, isochrones, and housing locations.<br /><br />
![CP255_Final_Presentation_Page_14](https://github.com/jcmchen/CYPLAN255_2024_Final_Project/assets/70067477/9b7dd1f6-8f08-4c47-9f1d-f2c0b8bbbeb4)

From the figure below, we can see that except housing in Zhongshan and Nangang districts, most housing located within the 5-min-walk distance from MRT stations
have higher price than those are not located within the 5-min-walk distance.
![CP255_Final_Presentation_Page_15](https://github.com/jcmchen/CYPLAN255_2024_Final_Project/assets/70067477/b8e18b42-6f10-4239-86d1-5cc5cdfb706c)
