# Recell Project

## Background: 

Buying and selling used smartphones used to be something that happened on a handful of online marketplace sites. But the used and refurbished phone market has grown considerably over the past decade, and a new IDC (International Data Corporation) forecast predicts that the used phone market would be worth $52.7bn by 2023 with a compound annual growth rate (CAGR) of 13.6\% from 2018 to 2023. This growth can be attributed to an uptick in demand for used smartphones that offer considerable savings compared with new models.

Refurbished and used devices continue to provide cost-effective alternatives to both consumers and businesses that are looking to save money when purchasing a smartphone. There are plenty of other benefits associated with the used smartphone market. Used and refurbished devices can be sold with warranties and can also be insured with proof of purchase. Third-party vendors/platforms, such as Verizon, Amazon, etc., provide attractive offers to customers for refurbished smartphones. Maximizing the longevity of mobile phones through second-hand trade also reduces their environmental impact and helps in recycling and reducing waste. The impact of the COVID-19 outbreak may further boost the cheaper refurbished smartphone segment, as consumers cut back on discretionary spending and buy phones only for immediate needs.



## Objective: 

The rising potential of this comparatively under-the-radar market fuels the need for an ML-based solution to develop a dynamic pricing strategy for used and refurbished smartphones. ReCell, a startup aiming to tap the potential in this market, has hired you as a data scientist. They want you to analyze the data provided and build a linear regression model to predict the price of a used phone and identify factors that significantly influence it.\

Exploratory data analysis (EDA) will also be carried out on the dataset to asnwer the following questions:
1. <a href = #link1>What does the distribution of used phone prices look like?</a>
2. <a href = #link2>What percentage of the used phone market is dominated by Android devices?</a>
3. <a href = #link3>The amount of RAM is important for the smooth functioning of a phone. How does the amount of RAM vary with the brand?</a>
4. <a href = #link4>A large battery often increases a phone's weight, making it feel uncomfortable in the hands. How does the weight vary for phones offering large batteries (more than 4500 mAh)?</a>
5. <a href = #link5>Bigger screens are desirable for entertainment purposes as they offer a better viewing experience. How many phones are available across different brands with a screen size larger than 6 inches?</a>
6. <a href = #link6>Budget phones nowadays offer great selfie cameras, allowing us to capture our favorite moments with loved ones. What is the distribution of budget phones offering greater than 8MP selfie cameras across brands?</a>
7. <a href = #link7>Which attributes are highly correlated with the used phone price?</a>


## Data Description:

The data contains the different attributes of used/refurbished phones. The detailed data dictionary is given below.

**Data Dictionary**
1. brand_name: Name of manufacturing brand
2. os: OS on which the phone runs
3. screen_size: Size of the screen in cm
4. 4g: Whether 4G is available or not
5. 5g: Whether 5G is available or not
6. main_camera_mp: Resolution of the rear camera in megapixels
7. selfie_camera_mp: Resolution of the front camera in megapixels
8. int_memory: Amount of internal memory (ROM) in GB
9. ram: Amount of RAM in GB
10. battery: Energy capacity of the phone battery in mAh
11. weight: Weight of the phone in grams
12. release_year: Year when the phone model was released
13. days_used: Number of days the used/refurbished phone has been used
14. new_price: Price of a new phone of the same model in euros
15. used_price: Price of the used/refurbished phone in euros
