# lora_roma
News on IOT and ML with Allan and Anders. To contribute to this document , for now send comments to f.luzio@converge.it

#### OCTOBER:2018
For the next meeting , i upload a serie of files (documentation and programs in python) about the sensor **BOSCH_BME680**.
I think this example is a good start point about raspberry , python , wheather station and transitting data to the cloud(Corlysis). A presto

#### JULY:2018


About weather data,  MetPy is a collection of tools in Python for reading, visualizing and performing calculations with [weather data.](https://github.com/Unidata/MetPy). 


----------------------------------------------------------------------------------------------
Another article (by Susan Li) about [time series](https://towardsdatascience.com/an-end-to-end-project-on-time-series-analysis-and-forecasting-with-python-4835e6bf050b)

Time series analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics of the data. Time series forecasting is the use of a model to predict future values based on previously observed values.

Time series are widely used for non-stationary data, like economic, weather, stock price, and retail sales in this post. We will demonstrate different approaches for forecasting retail sales time series. 
The Data

We are using Superstore sales data that can be downloaded from [here](https://community.tableau.com/docs/DOC-1236).

In the article there is Prophet:

Time Series Modeling with python in [Prophet](https://research.fb.com/prophet-forecasting-at-scale/)

Released by Facebook in 2017, forecasting tool Prophet is designed for analyzing time-series that display patterns on different time scales such as yearly, weekly and daily. It also has advanced capabilities for modeling the effects of holidays on a time-series and implementing custom changepoints. Therefore, we are using Prophet to get a model up and running.

------------------------------------------------------
Thank you all along our company’s support.  
We would like to let you know the launch Dual Channels LoRa gateway. 
          
Overview: LG02 & OLG02 are open source dual channels LoRa Gateway. They can be used to bridge LoRa wireless network to IP network via WiFi, Ethernet, 3G or 4G cellular. The
LoRa wireless allows users to send data and reach extremely long ranges at low data-rates. It provides ultra-long range spread spectrum communication and high interference immunity. With LG02/OLG02, user can build a long range wireless IoT solution rapidly. 

LG02 & OLG02 has Rich Internet Connection methods such as WiFi interface, Ethernet port and USB host port. These Interfaces provide flexible methods for users to connect their sensor networks to Internet.
LG02 & OLG02 can support the LoRaWAN protocol in single frequency and customized LoRa transmit protocol. The design of LG02 is using the Linux to directly control two sx1276/sx1278 LoRa modules which lets the LoRa can works in full duplex mode and increase the communication efficiency.

LG02 / OLG02 can be used to provide a low cost IoT wireless solution to support 50~300 sensor nodes.
 
Except LoRaWAN mode, LG02 / OLG02 can support other working on mutiply working mode such as: **LoRa repeater mode, MQTT mode, TCP/IP Client mode, TCP/IP Server mode** to fit different requirement for IoT connection. Click this link for more info about the modes. 
LG02 / OLG02 base on **sx1276** solution which provide a low cost for your IoT network connection. Compare to the cost with normal SX1301 LoRaWAN solution. the LG02 / OLG02 are only of its 1/4 or less cost. This make the LG02 / OLG02 very suitable to set up small scale LoRa network or use it to extend the coverage of current LoRaWAN network. 
 
Features: 
   --Open Source OpenWrt system
   --Low power consumption
   --Firmware upgrade via Web
   --Software upgradable via network
   --Flexible protocol to connect to IoT servers
   --Auto-Provisioning
   --Built-in web server
   --Managed by Web GUI, SSH via LAN or WiFi
   --Internet connection via LAN, WiFi, 3G or 4G
   --Failsafe design provides robustly system
   --2 x SX1276/SX1278 LoRa modules
   --Full–duplex LoRa transceiver
   --Two receive channels, and one transmit channel
   --Limited support in LoRaWAN/ Support Private LoRa protocol
   --Support upto 300 nodes
   --LoRa band available at 433/868/915/920 Mhz
   --Max range in LoRa: 5~10 km. Density Area:>500m
 
Typical Applications: 
   --Wireless Alarm and Security Systems
   --Home and Building Automation
   --Automated Meter Reading
   --Industrial Monitoring and Control
   --Long range Irrigation Systems
   --GPS tracker,etc   
   --LoRaWAN repeater

For more documents for LG02 / OLG02, please refer: 
•	Product Page: http://www.dragino.com/products/lora/item/135-lg02.html & http://www.dragino.com/products/lora/item/136-olg02.html 
•	Datasheet: http://www.dragino.com/downloads/index.php?dir=datasheet/EN/&file=Datasheet_LG02_OLG02.pdf   




#### JUNE: 2018 

1. To install Jupyter in Raspberry, you can see this:[Installing jupyter in Raspberry PI 3 ](http://www.instructables.com/id/Jupyter-Notebook-on-Raspberry-Pi/), but it would be sufficient this :
    - *sudo pip3 install jupyter* 
    - **jupyter notebook**   
 2. This [openmv software](https://openmv.io/pages/download) is a good start point for the NEW Camera iot.
 3. News from openmv [twitter world].(https://twitter.com/openmvcam)
 4. Time series ,  a data points collected at constant time intervals. [from analyticsvidhya ](https://www.analyticsvidhya.com/blog/2016/02/time-series-forecasting-codes-python/)


---------------

#### MAY: 2018


1. NEW Camera iot  [see:](https://openmv.io/).The OpenMV project is about creating low-cost, extensible, Python powered, machine vision modules and aims at becoming the “Arduino of Machine Vision“. Our goal is to bring machine vision algorithms closer to makers and hobbyists. We’ve done the difficult and time-consuming algorithm work for you leaving more time for your creativity.
2. New VisionKit from [Google:](https://aiyprojects.withgoogle.com/).The **AIY Vision Kit** from Google lets you build your own intelligent camera that can see and recognize objects using machine learning. All of this fits in a handy little cardboard cube, powered by a Raspberry Pi.
3. New Voicekit  from [Google:](https://aiyprojects.withgoogle.com/voice/). The *AIY Voice Kit* from Google lets you build your own natural language processor and connect it to the Google Assistant. All of this fits in a handy little cardboard cube, powered by a Raspberry Pi.

Anders said :

Another interesting field is [weather forecasting and machine learning:](http://stackabuse.com/using-machine-learning-to-predict-the-weather-part-1/)
