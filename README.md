---
csl: apa.csl
bibliography: RPiCitations.bib
---

**ActiveHouse**
===============

Project website <https://irwintr.github.io>

Prepared by Trenton Irwin

**Table of Contents**

1.  [Proposal](https://github.com/irwintr/irwintr.github.io/blob/master/README.md#proposal)

2.  [Executive
    Summary](https://github.com/irwintr/irwintr.github.io/blob/master/README.md#executive-summary)

3.  [Background](https://github.com/irwintr/irwintr.github.io/blob/master/README.md#background)

4.  [Methodology](https://github.com/irwintr/irwintr.github.io/blob/master/README.md#methodology)

5.  [Concluding
    Remarks](https://github.com/irwintr/irwintr.github.io/blob/master/README.md#concluding-remarks)

6.  [References](https://github.com/irwintr/irwintr.github.io/blob/master/README.md#references)

##	**Proposal**

The ActiveHouse Project would be a complete home monitoring system consisting of
multiple Arduino based sensor hubs in each room of your home wirelessly
connecting to a Raspberry Pi based base station which sends the data to the
server where it can be read by the app. Each sensor hub would be capable of
reading temperature, humidity, luminosity, carbon monoxide and other gas levels,
water consumption, power consumption, and it would have the ability to toggle
the built-in light. The power and water consumption sensors are detachable as
they would not necessarily be used in each room, thus creating a more modular
design. The app would allow users to view the current settings in each room and
over the complete house, toggle the lighting, and set a lighting schedule.

##	**Executive Summary**

As a Computer Engineering student, I’ll be using all of the skills I have
learned in the last 2 years in this program to complete this project. This
proposal requests the approval to build the hardware portion that will connect
to a database as well as to a mobile device application. The sensor hub hardware
will include a custom PCB with sensors and XBee wireless adapters and an Arduino
inside a custom printed box. The Base station hardware will include an XBee
wireless adapter connected to a Raspberry Pi. The database will store the sensor
data from each room. The mobile device functionality will allow users to view
the current settings in each room and over the complete house, toggle the
lighting, and set a lighting schedule. I may end up collaborating with the
greater Active House team later in the semester but I will not be working with
any companies. The hardware will be completed in CENG 317 Hardware Production
Techniques independently and the application will be completed in CENG 319
Software Project. These will be integrated together in the subsequent term in
CENG 355 Computer Systems Project.

##	**Background**

The problem solved by this project is that it provides a home monitoring
solution so that users homes can be controlled and monitored remotely through an
intuitive app. It will help people monitor their resource consumption as well
which may help drive down consumption.

There are several other home monitoring solutions on the market now[@4429263], but they
are usually integrated into either the thermostat or home security system. This
is one of the first projects I’ve seen where water and power consumption are
also monitored on a residential scale.

In the Computer Engineering Technology program I have learned about the
following topics from the respective relevant courses:

-   Electronic Devices and Circuits – Soldering experience

-   Database with Java – Setting up database

-   Electronic Circuits – Voltage Divider calculations

-   Technical Workplace Writing – Creating write-ups and technical drawings

-   Software Engineering – Creating project schedules

This knowledge and skill set will enable me to build the subsystems and
integrate them together as my capstone project.

##	**Methodology**

This proposal is assigned in the first week of class and is due at the beginning
of class in the second week of the fall semester. My coursework will focus on
the first two of the 3 phases of this project:  
Phase 1 Hardware build.  
Phase 2 System integration.  
Phase 3 Demonstration to future employers.

	*Phase 1 Hardware build*

The hardware build will be completed in the fall term. It will fit within the
CENG Project maximum dimensions of 12 13/16" x 6" x 2 7/8" (32.5cm x 15.25cm x
7.25cm) which represents the space below the tray in the parts kit. The highest
AC voltage that will be used is 16Vrms from a wall adaptor from which +/- 15V or
as high as 45 VDC can be obtained. Maximum power consumption will be 20 Watts.

	*Phase 2 System integration*

The system integration will be completed in the winter term.

*Phase 3 Demonstration to future employers*

This project will showcase the knowledge and skills that we have learned to
potential employers.

The tables below provide rough effort and non-labour estimates respectively for
each phase. A Gantt chart will be added by week 3 to provide more project
schedule details and a more complete budget will be added by week 4. It is
important to start tasks as soon as possible to be able to meet deadlines.

| **Labour Estimates**                                                                      | **Hrs**      | **Notes**                                                                                                                      |
|-------------------------------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------------|
| **Phase 1**                                                                               |              |                                                                                                                                |
| Writing proposal.                                                                         | 9            | Tech identification quiz.                                                                                                      |
| Creating project schedule. Initial project team meeting.                                  | 9            | Proposal due.                                                                                                                  |
| Creating budget. Status Meeting.                                                          | 9            | Project Schedule due.                                                                                                          |
| Acquiring components and writing progress report.                                         | 9            | Budget due.                                                                                                                    |
| Mechanical assembly and writing progress report. Status Meeting.                          | 9            | Progress Report due (components acquired milestone).                                                                           |
| PCB fabrication.                                                                          | 9            | Progress Report due (Mechanical Assembly milestone).                                                                           |
| Interface wiring, Placard design, Status Meeting.                                         | 9            | PCB Due (power up milestone).                                                                                                  |
| Preparing for demonstration.                                                              | 9            | Placard due.                                                                                                                   |
| Writing progress report and demonstrating project.                                        | 9            | Progress Report due (Demonstrations at Open House Saturday, November 7, 2015 from 10 a.m. - 2 p.m.).                           |
| Editing build video.                                                                      | 9            | Peer grading of demonstrations due.                                                                                            |
| Incorporation of feedback from demonstration and writing progress report. Status Meeting. | 9            | 30 second build video due.                                                                                                     |
| Practice presentations                                                                    | 9            | Progress Report due.                                                                                                           |
| 1st round of Presentations, Collaborators present.                                        | 9            | Presentation PowerPoint file due.                                                                                              |
| 2nd round of Presentations                                                                | 9            | Build instructions up due.                                                                                                     |
| Project videos, Status Meeting.                                                           | 9            | 30 second script due.                                                                                                          |
| **Phase 1 Total**                                                                         | **135**      |                                                                                                                                |
| **Phase 2**                                                                               |              |                                                                                                                                |
| Meet with collaborators                                                                   | 9            | Status Meeting                                                                                                                 |
| Initial integration.                                                                      | 9            | Progress Report                                                                                                                |
| Meet with collaborators                                                                   | 9            | Status Meeting                                                                                                                 |
| Testing.                                                                                  | 9            | Progress Report                                                                                                                |
| Meet with collaborators                                                                   | 9            | Status Meeting                                                                                                                 |
| Meet with collaborators                                                                   | 9            | Status Meeting                                                                                                                 |
| Incorporation of feedback.                                                                | 9            | Progress Report                                                                                                                |
| Meet with collaborators                                                                   | 9            | Status Meeting                                                                                                                 |
| Testing.                                                                                  | 9            | Progress Report                                                                                                                |
| Meet with collaborators                                                                   | 9            | Status Meeting                                                                                                                 |
| Prepare for demonstration.                                                                | 9            | Progress Report                                                                                                                |
| Complete presentation.                                                                    | 9            | Demonstration at Open House Saturday, April 9, 2016 10 a.m. to 2 p.m.                                                          |
| Complete final report. 1st round of Presentations.                                        | 9            | Presentation PowerPoint file due.                                                                                              |
| Write video script. 2nd round of Presentations, delivery of project.                      | 9            | Final written report including final budget and record of expenditures, covering both this semester and the previous semester. |
| Project videos.                                                                           | 9            | Video script due                                                                                                               |
| **Phase 2 Total**                                                                         | **135**      |                                                                                                                                |
| **Phase 3**                                                                               |              |                                                                                                                                |
| Interviews                                                                                | TBD          |                                                                                                                                |
| **Phase 3 Total**                                                                         | **TBD**      |                                                                                                                                |
| **Material Estimates**                                                                    | **Cost**     | **Supplier**                                                                                                                   |
| **Phase 1**                                                                               |              |                                                                                                                                |
| Cannakit Raspberry Pi v3                                                                  | \$99.99      | Amazon.ca                                                                                                                      |
| Arduino Uno SMD Rev3                                                                      | \$31.08      | Digi-key                                                                                                                       |
| Xbee S1 Trace Antenna (x2)                                                                | \$53.68      | Digi-key                                                                                                                       |
| Xbee Shield for Arduino                                                                   | \$22.77      | Digi-key                                                                                                                       |
| 3.5mm audio jack                                                                          | \$2.09       | Canada Robotix                                                                                                                 |
| Non-Invasive Current Sensor                                                               | \$13.19      | Canada Robotix                                                                                                                 |
| Adafruit Gas Sensor                                                                       | \$21.12      | Digi-key                                                                                                                       |
| Adafruit Light Sensor                                                                     | \$8.40       | Digi-key                                                                                                                       |
| Water Flow Sensor                                                                         | \$11.89      | Canada Robotix                                                                                                                 |
| 3 Pin Molex header                                                                        | \$0.39       | Canada Robotix                                                                                                                 |
| 12mm Buzzer                                                                               | \$1.99       | Canada Robotix                                                                                                                 |
| Adafruit Temperature and Humidity Sensor                                                  | \$19.70      | Digi-key                                                                                                                       |
| *Shipping*                                                                                | *\$6.95*     |                                                                                                                                |
| *Tax*                                                                                     | *\$37.22*    |                                                                                                                                |
| **Phase 1 Total**                                                                         | **\$330.46** |                                                                                                                                |
| **Phase 2**                                                                               |              |                                                                                                                                |
| Materials to improve functionality, fit, and finish of project.                           | N/A          |                                                                                                                                |
| **Phase 2 Total**                                                                         | **TBD**      |                                                                                                                                |
| **Phase 3**                                                                               |              |                                                                                                                                |
| **Phase 3 Total**                                                                         | **TBD**      |                                                                                                                                |

##	**Concluding remarks**

This proposal presents a plan for providing an IoT solution for a home
monitoring system. This is an opportunity to integrate the knowledge and skills
developed in the Computer Engineering program to create a collaborative IoT
capstone project demonstrating my ability to learn how to support projects. I
request approval of this project.

 

Systems Requirement Specifications
==================================

 

### Database Specifications

**Database Type**

For the ActiveHouse project I am using a MySQL database hosted on Munro. It can
be administered through phpMyAdmin.

**Database Tables**

There are four tables that are used in the Firebase.

1.  USERS

2.  HOUSE

3.  ROOM

4.  ROOM\_DATA

**USERS** is the table in which all users who sign up for the ActiveHouse
application are stored. They are given a key as a unique identifier.

**HOUSE** is the table in which the names of houses and their data are stored.
Each house is unique via an HOUSEID identification key within the table.

**ROOM** is the table in which the rooms in each house are stored. It contains
the HOUSEID that it corresponds with, a unique ROOMID and the room name.

**ROOM\_DATA** is the table where the sensor readings for each room are stored.
It is identified by the unique ROOMID.

**Work Breakdown**

There is no further work that needs to be done to the database.

 

### **Mobile Application Specifications**

**Graphical User Interface Specifications**

**MainActivity:** The login screen of the application is the first presented
upon launching the application. The user may enter already existing credentials
into EditText fields and login, or may choose to go to the sign up activity,
both navigations via Buttons. There is a checkbox to save the entered username
to local storage to be auto populated in future sessions.

**RegisterActivity:** The sign up screen of the application can be accessed from
the login screen. It has EditText fields for gathering new user information
including their HOUSEID. Without a HOUSEID, they cannot create a new account.
Incorrect EditText entries will be communicated via Toast message asking for
re-entry.

**HomeActivity:** This is the main screen of the app where the user can view the
current settings of the user’s house. There is a hamburger menu with links to
the other pages including one for each room in the home. Users can logout from
the menu bar.

**RoomActivity:** This page has the sensor data from an individual room
displayed. The user can interact with the page by toggling the light or light
schedule or setting the time on or off for the light. There is a hamburger menu
with links to the other pages including one for each room in the home. Users can
logout from the menu bar.

**RoomViewActivity:** The room view activity is a listview with all of the rooms
in it. Users can select the room they wish to view and be taken to the
RoomActivity page for that room.

**Application Work Breakdown**

There are a few small bugs that I need to patch, but the app is working and
pretty much complete.

 

### **Web Specifications**

**Web Service Specifications**

The web service is written in php and hosted on Munro. It can be accessed at
munro.humber.ca/\~n01046059/ActiveHouse.

**Web Work Breakdown**

The side of the web service that interacts with the mobile app is complete and
does not require any changes. I do need to write the side of the web service
that connects to the Raspberry Pi to send and receive sensor data. Additionally
I need to write a program to run on the Raspberry Pi to send the data to the
server.
