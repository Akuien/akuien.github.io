---
title: "Dentistimo"
excerpt: "A microservice distributed dentist booking system for users in Gothenburg. [GitHub repo](https://github.com/Akuien/Dentistimo-documentation)<br/><img src='/images/dentistimo_architecture_500x300.png'>"

collection: portfolio
---

Dentistimo is a web application that allows the residents of Gothenburg to choose a dentist from the map and book dentist appointments with ease. Dentistimo is a distributed system made of 5 components. The system's components are communicating with each other through an MQTT middleware by sending and receiving lightweight messages, and our main goal was to create a responsive interface frontend accessing different functionalities that supports communication over MQTT using protocol through a websockets, which will allows the asynchronous communication with the server.

MIcroservices Components
* [User interface](https://github.com/Akuien/Dentistimo-userinterface)
* [Booking Handler](https://github.com/Akuien/Dentistimo-bookinghandler)
* [Dentistry Handler](https://github.com/Akuien/Dentistimo-dentisthandler)
* [User Handler](https://github.com/Akuien/Dentistimo-userhandler)
* [Timeslots Generator](https://github.com/Akuien/Dentistimo-timeslotgenerator)


