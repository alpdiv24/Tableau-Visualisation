## Tableau-Visualisation
## Author: Alpesh Chocatiya, 03-10-2022
## Dataset Info:

Rows: 51290
Columns: 24 
 #   Column          Non-Null Count  Dtype         
---  ------          --------------  -----         
 0   Row ID          51290 non-null  int64         
 1   Order ID        51290 non-null  object        
 2   Order Date      51290 non-null  datetime64[ns]
 3   Ship Date       51290 non-null  datetime64[ns]
 4   Ship Mode       51290 non-null  object        
 5   Customer ID     51290 non-null  object        
 6   Customer Name   51290 non-null  object        
 7   Segment         51290 non-null  object        
 8   City            51290 non-null  object        
 9   State           51290 non-null  object        
 10  Country         51290 non-null  object        
 11  Postal Code     9994 non-null   float64       
 12  Market          51290 non-null  object        
 13  Region          51290 non-null  object        
 14  Product ID      51290 non-null  object        
 15  Category        51290 non-null  object        
 16  Sub-Category    51290 non-null  object        
 17  Product Name    51290 non-null  object        
 18  Sales           51290 non-null  float64       
 19  Quantity        51290 non-null  int64         
 20  Discount        51290 non-null  float64       
 21  Profit          51290 non-null  float64       
 22  Shipping Cost   51290 non-null  float64       
 23  Order Priority  51290 non-null  object        
dtypes: datetime64[ns](2), float64(5), int64(2), object(15)
memory usage: 9.4+ MB

## Image1: Diff in Avg Sales - quarterly
This chart shows % difference in average sales for each category from the previous year for each Quarter.
![Diff in Avg Sales - quarterly](https://user-images.githubusercontent.com/114546267/193604744-c87663a5-92c7-49c6-86f3-92485453b247.png)
