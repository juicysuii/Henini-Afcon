# HENINI AFCON ThinkAI Hackathon

## Introduction

HENINI AFCON is an intelligent chatbot developed during the ThinkAI Hackathon. It aims to assist football fans in planning their trips to various cities in Morocco for the African Cup of Nations (AFCON) 2025. The chatbot provides comprehensive information about the cities, transportation options, accommodations, activities, safety tips, and other essential details to ensure a well-planned and enjoyable experience for tourists.

## Features

+ **City Information** : Get detailed insights into the cities hosting AFCON 2025 matches, including cultural landmarks, historical sites, and local attractions.
+ **Transportation** : Explore various transportation options such as flights, trains, buses, and taxis to reach your destination conveniently.
+ **Accommodation** : Discover recommended hotels, guesthouses, and other lodging options suitable for different preferences and budgets.
+ **Activities** : Find exciting activities and experiences to enhance your trip, ranging from sightseeing tours to adventure sports.
+ **Safety Tips** : Receive valuable safety tips and guidance to ensure a secure and hassle-free travel experience.
***Future Upgrades***: The project is designed to be scalable and can be extended to cover other events, such as the FIFA World Cup 2030, or any future events hosted by Morocco.

## APIs Used / Data Collected
HENINI AFCON utilizes the following APIs to provide accurate and up-to-date information:

   * **Google Directions API**: This API is used to calculate and provide directions between locations, ensuring that users have the best routes and transportation options for their travels.
   * **Google Geocoding API**: This API is used to convert addresses into geographic coordinates, which are essential for mapping and location-based services within the chatbot.

The following websites were used to collect data about activities and safety in Casablanca:

+ [Things to do in Casablanca](https://northafricadreamin.com/things-to-do-in-casablanca/) 
+ [Tourist Attractions in Casablanca](https://www.planetware.com/tourist-attractions-/casablanca-mar-c-cas.htm)
+ [Fun Things to Do in Casablanca](https://wanderlog.com/list/geoCategory/849176/fun-things-to-do-in-casablanca-fun-attractions-and-activities)
+ [Top Things to Do in Casablanca](https://www.journalofnomads.com/things-to-do-in-casablanca-morocco/)
+ [The Top 10 Things to Do and See in Casablanca](https://theculturetrip.com/africa/morocco/articles/the-top-10-things-to-do-and-see-in-casablanca")
+ [Is Casablanca Safe?](https://www.moroccotoursagency.com/is-casablanca-safe/)
+ [Safety in Casablanca](https://stayhere.ma/en/blog-en/2023/05/05/is-casablanca-safe-2/)

## Models Used
To generate text and provide responses, HENINI AFCON uses the following models:

1. **Hugging Face Endpoints**:

      + meta-llama-3-8b-instruct-tt
      + meta-llama-3-8b-instruct-xcn
  
      Initially, we used these Hugging Face models to generate text. However, both models had a limitation in terms of output tokens, which affected the completeness of the responses.

2. **Replicate Model**:

     + **meta-llama-3-70b-instruct**

     To overcome the token limitation issue, we switched to the Replicate **model meta-llama-3-70b-instruct**. This model provided a more robust solution, enabling longer and more detailed responses without the previous token limitation.

## How to Use

1. **Initial Questions** : When you first interact with HENINI AFCON, you'll be asked a series of questions to personalize your experience. These questions may include:

    * Your name
    * The teams you want to watch
    * Whether you have already booked a hotel or not
    * Which match you want to watch

3. **Trip Planning** : Based on your responses, HENINI AFCON will generate a customized trip plan for you. This plan will include:

      * City recommendations based on the matches you want to watch
      * Transportation options to and within the chosen cities
      * Accommodation suggestions tailored to your preferences
      * Activities and attractions to explore during your stay
      * Safety tips and essential information for a smooth travel experience

4. **Chatbot Customization**: HENINI AFCON provides a chat interface where you can further customize your trip plan. You can ask additional questions, make specific requests, or seek more detailed information about any aspect of your trip.

5. **Feedback** : We value your feedback! If you have any suggestions or encounter any issues while using HENINI AFCON, please don't hesitate to share your thoughts. Your input will help us improve the chatbot and enhance the user experience for future users.

## Contributors 
* Youssef ABERKANE
* Oumaima BENDIDI
* Oumayma BENNOUNA


## Acknowledgments
We would like to express our gratitude to the organizers of the ThinkAI Hackathon for providing us with the opportunity to develop HENINI AFCON. Additionally, we appreciate the support and guidance from our mentors throughout the project.
