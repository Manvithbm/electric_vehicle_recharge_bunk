# electric_vehicle_recharge_bunk
A full-stack web application to locate, manage, and book electric vehicle (EV) recharge stations. This project aims to promote sustainable transportation by making EV charging more accessible and efficient for users.

# Project Architecture
![image](https://github.com/user-attachments/assets/dc5b6965-8a37-493d-8a72-3a99c36bf26e)

# Built With
Firebase
JavaScript
HTML
CSS
JQuery

# Features
Authenticated Users can find & locate the nearest EV Charging stations and for authenticated users they can only view the bunks details such as contact, location, slots vacancy and also total slots.

Admins(Bunk Managers) can do the same as normal users, and as additional benefits they can ADD/UPDATE/DELETE their own bunk details.

For admins there is a special page named as "manage-bunks.html", there they can the CRUD operations.

Admins can do the CRUD operations in the nice Admin-Interface, which makes it easy to add/modify/delete courses.

There are two links to locate the charging stations nearby using the name of place or location

First one "Locate Charger", which filters the bunks only according to the location entered even there are no freeslots available.
Second one "Slots Availability", which additionally filters all the nearby bunks which have minimum of 2 freeslots on page loading. When user starts to search for any location, the bunks results are in location are showing with the freeslots filter.
Additionally there is a profile page for authenticated users to view their login details.


