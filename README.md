# Crime Monitoring and Police Assistance
This project was build up in a hackathon at IIT(ISM) Dhanbad - HACKFEST'17


Main idea : 
If a person is facing a threatening situation or is in danger of any sort, he/she will try to reach for help. Suppose the person is going through an area where he feels threat of any kind, then the first and immediate reaction of a person would be to shout for help. Moreover, in case the person is really in danger he wouldn't get enough time to call anyone or run as soon as he acknowledges the threat becasue the criminal could have planned everything in order and leaves no chance for the victim to reach out to his cellular device. The solution to this is to provide immediate police help at the spot from where the "shout for help" was called out.

This shout for help can be easily detected with any electronic device that a person is carrying with himself. The obvious one is our mobile phone but sometimes when it is kept in the pocket, the audio recorder wont work properly. The perfect solution would be to implement the audio recorder in watch. Moreover, commonly available smart watches too have working audio recorders. 

Keeping this in mind, we have designed a system where the smart watch of the person which is connected to the android mobile of the person is constantly listening to "Help ME" or similar sound/voice command  with or above certain level of loudness and if it detects the latter, an application will immediately start running in the mobile and send the query in the form of current location (geographical coordinates, address) and contact number to a web server. The web server will pass this on to an application(desktop app) running on a system in nearest police station. The web server will have an algorithm embedded so that it can search for the police station that is nearest to the query point.
As soon as the desktop application gets the query it would populate the latter using a marker on Google Maps. Other information such as contact information, name of the person, etc. would be received as well by the app. Then the required action could be taken.






Technologies used to build the system : 

1. Smart watch (any smart watch even the cheaper versions would work, it must've audio recorder and bluetooth)

2. Android (for mobile phone application of the person)

3. JavaFX (desktop application)

4. NodeJs, MongoDB (Web server and database)
