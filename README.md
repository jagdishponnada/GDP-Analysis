# GDP-Analysis-of-India

## NITI Aayog: Background

NITI Aayog (National Institution for Transforming India) is a policy think tank of the Government of India; 
it provides strategic inputs to the central and the state governments to achieve various development goals. 
In the past, NITI Aayog has played an important role in initiatives such as Digital India, Atal Innovation Mission 
and various agricultural reforms and have designed various policies in education, skill development, water management, 
healthcare, etc. 
 
 
## Project Brief:

You are working as the chief data scientist at NITI Aayog, reporting to the CEO. The CEO has initiated a project wherein the NITI Aayog will provide top-level recommendations to the Chief Ministers (CMs) of various states, which will help them prioritise areas of development for their respective states. Since different states are in different phases of development, the recommendations should be specific to the states.
 
The overall goal of this project is to help the CMs focus on areas that will foster economic development for their respective states. Since the most common measure of economic development is the GDP, you will analyse the GDP of the various states of India and suggest ways to improve it.
 
## Understanding GDP:

Gross domestic product (GDP) at current prices is the GDP at the market value of goods and services produced in a country during a year. In other words, GDP measures the 'monetary value of final goods and services produced by a country/state in a given period of time'.
 
GDP can be broadly divided into goods and services produced by three sectors: the primary sector (agriculture), the secondary sector (industry), and the tertiary sector (services).
 
It is also known as nominal GDP. More technically, (real) GDP takes into account the price change that may have occurred due to inflation. This means that the real GDP is nominal GDP adjusted for inflation. We will use the nominal GDP for this exercise. Also, we will consider the financial year 2015-16 as the base year, as most of the data required for this exercise is available for the aforementioned period.
 
## Per Capita GDP and Income:

Total GDP divided by the population gives the per capita GDP, which roughly measures the average value of goods and services produced per person. The per capita income is closely related to the per capita GDP (though they are not the same). In general, the per capita income increases when the per capita GDP increases, and vice-versa. For instance, in the financial year 2015-16, the per capita income of India was ₹93,293, whereas the per capita GDP of India was $1717, which roughly amounts to ₹1,11,605. 
 
India ranks 11th in the world in terms of total GDP; however, it lies at the 139th position in terms of per capita GDP.

All Datasets are goverment dataseet from (URL: https://data.gov.in/ )

## Preprocessing and Methodologies
In this assignment we used various EDA techniques to explore the dataset.We took the help of visualization to do gain insights from the dataset. We used matplotlib and seaborn libraries for visualization. We did null value imputation on few columns where necessary with central values.


## Key Results
- Mizoram is the consistently growing state and Goa is consistently declining as per GSDP.
- Tamil Nadu has the highest GSDP where as Sikkim has the lowest GSDP.
- Goa has highest per capita GDP where as Bihar has lower per capita GDP.
- The percentage contribution of Primary, Secondary and Tertiary sectors to the overall GSDP of all states combined is 20,26 and 46 percentage respectively.
- Dropout in upper primary has highest negative correlation with the per capita GDP .

## Insights
- Tertiary Sector contributes the most to the GSDP overall.
- Category of states which performs equally good in all sub sectors performs better as compared to over dependency on single sub sector.
- Agriculture is a top contributor in all the categories of states. No doubt India is a agriculture based economy.
- Real estate is one such sub sector whose contribution is gradually increasing from C4 to C1.
- The higher the drop outs in upper primary education lower is the per capita GDP.



## Recommendations

- ### For C3 and C4 :
Government should reduce the over-dependence of the rural population on agriculture as a source of income . A suitable push needs to be given to
infrastructure development ,industrial and services sector growth in rural areas. It is also important to impart skills to the rural workforce appropriately to enable them to get absorbed in the non-agriculture sector.

- ### For C1 and C2 : 
India being a consumer driven economy, it would be a wise decision to invest in manufacturing sector . India is also aggressively working on “Make in India” , so its better to align all the states to that vision. This will not only generate more employment but also will increase the purchasing power of the population. This will encourage people to invest and will help the real estate sector grow which is already the leader in GDP.

- Government should also invest in construction sector as a better infrastructure would ease the transfer of the manufactured goods to other states. This will improve trade relations among the states resulting in overall improvement in GDP . 
- The upper primary education is more negatively correlated with the per capita GDP as compared to primary and secondary education. We can infer that, the higher the drop outs in Upper primary education, the lower will be the per capita GDP. Government should take necessary steps like funding schools or reducing the fee to reduce the dropouts.
- Government should also educate the ignorant parents on importance of primary education (which is least correlated to per capita GDP) . Increase in number of enrolments to primary education would improve the chances to transition to upper primary and thereby improving the numbers in upper primary education.
- Tertiary sector (Financial services, Public administration, Railway etc.) ,being the highest contributor creates a lot of job opportunities for skilled labour. Improving the dropout rates will generate more skilled labour which in turn will help the tertiary sector to prosper.

