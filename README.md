# Small project to get to know Node-Red
## Overview:
In this repository I want to present a Low-code programming tool for event-driven applications called Node-Red.\
Node-RED is a flow-based programming tool, and this tool can build web applications for any software applications easily, such as IoT data handling, standard web applications, web APIs, and so on.\
It comes really in handy, I have used it in my technical internship to visualise data and send sms in case of an alarm triggering. So, I will present some small projects and things we can do using node-Red.

### Small projects:
1. **Visualize the value of the current temperature using the gauge and turn on the convenient led**
In order to get weather forcast for a specific city in a country, you have to use an API (its definition is👇🏻), I suggest openweathermap.org, there is as well a lot of ways to obtain result (by city name, by ID, by ZIP code). If you choose by city name you will get this API call https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}, you have to change only the city name by yours and add your API key. For example, https://api.openweathermap.org/data/2.5/weatherq=casablanca&appid=276d2beb8a167540bf628b3a379a7fe3&units=metric. I added units as **metric** to give the value of temperature in °C. If you type the request it will return by default a json code.
By using some of Node-Red elementary cores I managed to visualize in a gauge the current temperature in °C and turn on the convenient temperature.
<img src="https://www.moroccoworldnews.com/wp-content/uploads/2020/07/Facts-About-the-Map-of-Morocco-1024x683.jpg" width="300" height="300">
To see the result we open the ui dashboard and here is the result:
<img src="https://www.moroccoworldnews.com/wp-content/uploads/2020/07/Facts-About-the-Map-of-Morocco-1024x683.jpg" width="300" height="300">
If you want to import the project you will find ☝🏻 the complet json code.

2. Read & write data from serial port
For IOT projects we need so much a tool to visualize our results, so by using the node COM of Node-Red the need is met.
You will find the code json ☝🏻.

3. 

## 📌 Keywords:
	APIs:
API is the acronym for Application Programming Interface, which is a software intermediary that allows two applications to talk to each other. Each time you use an app like Facebook, send an instant message, or check the weather on your phone, you’re using an API. To illustrate this here is an analogy: The waiter is the messenger – or API – that takes your request or order and tells the kitchen – the system – what to do. Then the waiter delivers the response back to you; in this case, it is the food.

## 🔧 Tools:
- Node-Red installed locally (on your computer or on a raspberry pi).
- Create an API account in open weather.

## 🖇️ Resources:
- https://andy6804tw.github.io/awesome-template/api-application-programming-interface/#sectionTest
- https://openweathermap.org/api
