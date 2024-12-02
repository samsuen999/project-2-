# project-2-

# Group4Project2

## Group 4 Team Members:

- Abhi Malik [@Malik01010](https://github.com/Malik01010)
- Eric Kho [@ek29262](https://github.com/ek29262)
- Arish Petani [@Arishpetani](https://github.com/Arishpetani)
- Samuel Suen [@samsuen999](https://github.com/samsuen999)
- Dan [@danmmosu](https://github.com/danmmosu)



## Description of Dataset:

Our dataset was obtained from https://catalog.data.gov/dataset/border-crossing-entry-data-683ae. It contains border entry data into the United States through land ports. It includes the borders that the United States shares with Canada and Mexico. The data is taken by the United States Customs and Border Protection. 

The dataset contains dimensions that capture the mode of transportation, the date of crossing (month, year), the volume on the date, the name of the port and the city the port belongs to. The data goes as far back as 1996 and as recent as January 2024.


## Data Manipulations

In tableau we set the date of crossing as a date data type. We also renamed certain dimensions in tableau to make more sense, such as renaming "value" to "traffic" which represents the amount of border crossings for a given data point.

## Considerations:

There is considerable more border activity between the United States and Mexico. Because of this our group decided to focus our analysis around the United States and Mexican border.


![image](https://github.com/user-attachments/assets/e42fff08-eb7e-4c4c-972a-821acd06defd)

![image](https://github.com/user-attachments/assets/9d2499c2-672b-4c07-b6d6-37e064c2a8df)                   


Covid-19 heavily decreased the amount of border crossings. The border was closed for non-essential travel, and it took some months for the amount of border crossings to recover as restrictions loosened up. A sharp decline can be seen in April 2020 which marks the peak of Covid-19 in the United States.

![image](https://github.com/user-attachments/assets/3e82a0f9-2aef-4b33-a815-955fa424e6a4)



## Question 1:

Are there any trends in border crossing based on time dependent factors, such as seasons, holidays, or other special calendar events?

This question can help dictate if their are any fluctations in border crossing volume based on time dependent factors. From the fluctations we can try to create some explanations. By anticipating an increase in border crossing volume Customs and Border Protection can prepare their resources to accomodate the amount of traffic coming in. This information can also help drive policy decisions and can be used to help determine the economic impact of border crossing activity.

![image](https://github.com/user-attachments/assets/6eff26eb-ca47-4e19-b79a-beb0f7a5df1b)

Migration over many years follows a consistent pattern. 

![image](https://github.com/user-attachments/assets/75cfb09e-b418-40a3-bfbb-cc6a0547542a)

Migration peaks in the summer months and falls in the winter months. This suggest that the weather brought about by winter creates adverse conditions which discourages travel. There is a slight climb in the month of December. This suggest families are crossing the border to see relatives for Christmas and that there is increased movements of goods to meet increased demand for the holidays. After December border crossings continue to fall until reaching their lowest point in February. 

## Question 2:

What are the trends concerning transportation modes? Do different ports of entry see more of certain types of transportation?

This question helps to identify the main purpose each port serves. By understanding the main use of each port policy decisions and infastructure can be created to be service each port's needs. A port mainly servicing trucks would need more intensive searches and documenting of goods coming in by Customs and Border. Whilst a port mainly serving pedestrians and family vehicles would need different types of processing and customs, such as more biometrics or humanitarian services.

![image](https://github.com/user-attachments/assets/6f529d67-3b10-4652-b6b3-42c983572ce4)

This first graph shows the ports with the highest passenger vehicles and pedestrian crossings. San Ysidro takes in the highest amount of this kind of traffic. Thus it should be serviced to accomodate this kind of traffic and volume. If policy makers felt the need to restrict migration most unrelated to trade they would most likely target these ports and slow migration through them. 

![image](https://github.com/user-attachments/assets/ed19ac2c-cee9-4132-8eb5-b44bf2b7a310)

This graph shows the ports with the highest amount of trucks coming in. The movement of goods is facilitated by trucks, and indicates trade and commerce. Laredo has the highest truck volume and makes up 57.6% of land port trade in the state of Texas, or about $234.7 billion in the year 2018 (Texas.GOV). Monitoring this port can help forcast finances, and drive economic decisions for policy makers. 

## TWB File

The Tableau workbook file is attached to the repository.
