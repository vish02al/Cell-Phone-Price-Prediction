# Cell-Phone-Price-Pridiction1
● Problem Statement
● Bob has started his own mobile company. He wants to give a tough fight to big companies likeApple, Samsung etc. He does not know how to estimate the price of mobiles his company creates. In this competitivemobile phone market, you cannot simply assume things. To solve this problem he collects sales dataof mobile phones of various companies. Bob wants to find out some relation between features of a mobile phone(eg:- RAM, Internal Memoryetc) and its selling price. But he is not so good at Machine Learning. So he needs your help to solvethis problem. In this problem we do not have to predict the actual price but a price range indicating how high the price is.

● AIM =  The objective of the dataset analysis is to predict the price range of mobile phones based on specifications such as Battery Power, 3G Enabled, WiFi, Bluetooth, RAM, and other relevant features.

● Domain Analysis:-
 The 'Cell Phone Prediction' dataset is intricately linked to the telecommunications industry, with a concentrated focus on the mobile phone sector. This dataset is instrumental in understanding and analyzing trends, preferences, and technological advancements within the realm of mobile devices. It offers valuable insights into various features and specifications of cellphones that potentially influence their market positioning and consumer appeal.

● Data Field.

battery_power = Total energy a battery can store in one time measured in mAh,
blue - Has bluetooth or not,
clock_speed = speed at which microprocessor executes instructions,
dual_sim = Has dual sim support or not,
fc = Front Camera mega pixels,
four_g = Has 4G or not,
int_memory = Internal Memory in Gigabytes,
m_dep = Mobile Depth in cm,
mobile_wt = Weight of mobile phone.
n_cores = Number of cores of processor,
pc = Primary Camera mega pixels,
px_height = Pixel Resolution Height,
px_width - Pixel Resolution Width,
ram = Random Access Memory in Megabytes,
sc_h = Screen Height of mobile in cm,
sc_w = Screen Width of mobile in cm,
talk_time = longest time that a single battery charge will last when you are,
three_g = Has 3G or not,
touch_screen = Has touch screen or not,
wifi = Has wifi or not,
price_range = This is the target variable with value of 0(low cost), 1(medium cost), 2(highcost) and 3(very high cost).
● The dataset has been thoroughly examined, and it has been confirmed that there are no missing values, ensuring completeness and reliability of the data for analysis.

● Conclusion:-
We try with multiple machine learning model to predict cell phone price accurately. among them the logistic regression works well and delivering an exceptional accuracy score of 97% .our model is performing quite well across all classes with high accuracy.

● Suggestion:-
Through this further analysis i want to suggest BOB that the price of mobile is increasing or decreasing are based on features of the mobile.
mobile with there price range :
0: Low Price Range - Phone with basic feature are in category of low price range.
1: Medium Low Price Range - in this price range of mobile phone have better feature as compare to low price range mobile phone, features are like better camera and more ram.
2: Medium High Price Range - In this price range, the mobile phone have better feature and good performance nad inheld with advanced technology like higher camera megapixels and better processor.
3: High Price Range - this range of mobile phones are loded with top feature, high quality camera, large memory, excellent battery power and advanced technology.
And my suggestion is that based on features of mobile you can select price range of mobile.
