# Yelp_Featured-Andriod-APP
Yelp_Featured Andriod APP Built in summer 2022 </br>
Source Code Please Refer to : </br>
https://github.com/CPEN321HELP/CPEN321 </br>

## Purpose
The purpose of this project is to help UBC staff, students and visitors from all around the world (target audiences) to explore and review posts, restaurants, entertainments, and study spaces at UBC. We decided to use google map service besides the Google authentication service as our additional external service, which helps users to locate facilities. For each facility, information such as their title, description, picture, and location will be shown. Users can rate four types of facilities mentioned above and comment on them (considered as reviews for our app), including texts, and emoji; reviews can be upvoted or downvoted. If users discover a new place on campus, they may add the place on the app through the “add facilities” tab. If there are duplicated facilities, the admin will remove them accordingly. Moreover, if a user gets a comment on their post, they will receive a notification on their device within 20 seconds. Users can search the keyword of the name of a facility in a search bar on top of the screen after they select a category (post, restaurant, entertainment, study space) from the home page (the result will display if the title contains the matching keyword). Moreover, if an user has questions about our app, including app settings, app functionalities, and profile settings, they can head over to the ChatBot interface on the main menu. This functionality allows the user to select from a list of popular questions and the chatBot will answer accordingly. Our complexity idea is a slick UI that enhances the aesthetics of our app and makes the user experience more enjoyable. The slick UI has a harmonic colour theme, animations, day/night mode and smoothness in response and in transition. Our complexity idea also has a credit calculator that grants user credits based on their contributions including rating and reviewing facilities, reporting inappropriate comments and adding new places to the app. They will get levels corresponding to the points they earn and it will show up on their profile. However, if a user gets reported with inappropriate behavior such as making offensive reviews, their credit will be deducted, or even blocked from signing into our app. Notification will take place starting from the second review of a facility to notify all users who have commented on the facility or take place after the user’s report has been processed. 
###Backend: 
We updated our design module, submodule, and interface. Achieve high cohesion and low coupling. We modularized backend code into different folders.
Now the final modularized backend modules are user, Administrator, reviewManagement and facility.  Both the reviewManagement and facility module calls the user module. The “reviewManagement” module updates user credit once an admin finishes processing the report sent by a user, user credit will get updated if the report is deemed to be valid.  Similarly, for user reporting a facility, if the report is deemed to to be a true user will be granted with credit.  
###Frontend:
We added another use case to our app: FAQ. This use case is associated/linked with the “user” (an actor name), and has no extensions or including/included use cases. It is a new, separate use case. We implemented this use case as a chatBot that helps to answer FAQs. This functionality opens a chat interface and prompts the user to select from a list popular questions (FAQ), and then the chatBot will answer each selected question accordingly. This functionality has no association with the backend. We added this functionality to slightly extend the scope of our project to make sure it meets the minimum requirement.  
General:
We also updated some of the test designs in M6 that we wrote, we have updated them in this document. We also updated our non-functional requirements (M3, M6). 

