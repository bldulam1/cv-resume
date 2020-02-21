# BRENDON DULAM
### Yokohama, Kanagawa Japan
### brendondulam06@gmail.com · linkedin.com/in/bldulam1

A highly motivated and output driven software developer with a focus on web applications development, data analysis and automation, looking for a Full-stack developer role. 


## SKILLS
### Backend
* GO
* Python
* NodeJS
* Express

### DevOps
* GitHub CI/CD
* CircleCI
* Docker
* PM2.js

### Frontend
* HTML / CSS / Javascript
* React
* Gatsby
* Next
* Material UI
* Bootstrap
* Bulma

### Design
* Adobe XD
* Inkspace

### Shell Scripting
* Powershell
* CMD

### Authentication
* OAuth for Google and Facebook
* Microsoft Authentication Library

### Code Management
* Git
* Gitlab
* GitHub

### Development Environments
* Ubuntu
* Windows Server 2016
* Windows 7
* Windows 10

## EXPERIENCE
### AUG 2018 – PRESENT
### SOFTWARE ENGINEER (PRODUCT ASSURANCE), VEONEER JAPAN
My main role is to write scripts that could assign hundreds of servers to perform simultaneous processes on thousands of files. Worked as a full-stack developer of a scalable, distributed data management tool, used in making inventory of data recordings and selecting files to be used as input for various processes. The application is using a microservice architecture whose backend is written in NodeJS, GO, and Python. The following are the projects that I worked with.

#### Data Management Tool 
*August 2018-July 2019*
* In this project I worked as a frontend and backend developer of a system called Clarity, which is used to support Japan OEM projects' data visualization and data management. 
*	This tool is used mainly for searching data and provide cloud computing services using the recorded data. 
*	It is a multi-page web application using Gatsby, React, Material UI in the frontend. The backend microservices are written mainly in NodeJS, and other services are written in GO (Golang), and Python. The databases for each microservice use MongoDB.
*	It can crawl all the files (data recordings) in the data center and store the locations of those data in a MongoDB database. The total capacity of the data center is in the petabytes scale, a single file ranges from 1 GB to 1TB of data recording containing videos, CAN Data (Radar), and Lidar packets.
*	The data can be used as input for various processes like HIL, SIL, Simulations, Data extraction, etc. These processes are distributed across hundreds of servers, and the processes are trackable in the application’s UI.

#### PCAP Decoder
*July 2019 – September 2019*
*	The purpose of this tool is to extract the X, Y, Z, radius, azimuth, elevation angle, intensity (point cloud points) of the returned signal of each laser in a Velodyne Lidar. Some existing tools like Veloview can do this job through Python script, but it is slow and does not support multiple lidar PCAP file. So, I decided to write a compiled binary tool using the GO programming language.
*	Through this project, I gained a deep understanding of the data structure of a Lidar PCAP file.
*	This tool is now used in production across multiple countries in Veoneer.
*	Performance-wise, this tool can extract a PCAP file’s point cloud 30 times faster than Veloview.
*	This tool supports VLP16, VLP32, and VLS128 Velodyne lidars
*	This project reinforced my understanding of the 7 layers of the Open System Interconnection (OSI) model. 
*	I also used most Wireshark to debug the visualize the hexadecimal bit-wise encoding of the PCAP file

#### Machine Learning-Based Labelling Tool for Lidar and Camera
*September 2019 – Present*
*	The purpose of this project is to provide ML-based annotation tool for images, and lidar data, which will be used as a ground truth for the Radar CAN data labels.
*	This tool consists of three pipelines namely, the Camera, Lidar and Radar Labelling pipelines. These three pipelines generate separate CSV files containing the detected objects per time frame/cycle. The Radar CSV file is compared against the Lidar and Camera CSV files. The objects are linked using the azimuth, object size information.
*	Using the open-sourced Mask RCNN and Microsoft’s COCO dataset, I built a server whose purpose is to label images from the data recordings.
*	The Lidar point cloud labelling algorithm is currently under development. Some open sourced libraries like PointNet and 3DmFV algorithms are also considered.
*	The segmentation of the Lidar uses DBSCAN of Python’s Scikit-learn DBSCAN package.
*	So far, the tool gives 70% accuracy labels. The incorrect and missed labels are going to be corrected using human effort

#### Tools Inventory System
*January 2020 – Present*
*	As part of the 5S initiatives in the Product Assurance Department, I made a proposal to build an application that stores the information of all the tools in the department. This will lessen the time to search for a tool. It can also track the condition of each tool and prevent purchasing redundant tools.
*	I built the backend using a microservice architecture, whose API is using GraphQL.
*	The frontend is outsourced to a team in India.

### **OCTOBER 2017 – AUGUST 2018**
### LED DESIGN AND DEVELOPMENT ENGINEER, KOTO ELECTRIC CO. LTD.
My work here is developing LED fixtures for customer requirements in the field of Marine Lighting (Fishing lamps), Hospital specific LED lighting, lighting for trains. 
*	Developed a Dimmer controller for LED lighting fixtures using an Arduino microcontroller.
*	Developed a controller for 64 x 128 RGB dot matrix LED panels using Arduino.
*	Created assembly and layout drawings using AutoCAD 2017.
*	Coordinated with suppliers from China, sales representatives, and machine industries for aid in project completion.

### JULY 2015 – OCTOBER 2017
### ELECTRICAL ENGINEER, ROKKO & ASSOCIATES
After graduating from the university, I worked In Rokko as an electrical engineer in the construction industry. Our project is a 35-floor twin tower building in Kokubunji, Tokyo. As a newcomer, I am in-charged mostly in creating the electrical layouts of each room in some floors of the building.
*	Used AutoCAD to draw electrical wiring plans.
*	After improving my Japanese, I worked as a facilitator during the morning meetings (朝礼). I inspected the risk management plans of each subcontractor. I also attended coordination meetings with the general contractor.
*	I inspected the quality of the wirings done by the subcontractors. The quality checks include incorrect mapping of the lighting and switch, unprotected crossing of high and low voltage wirings, short circuit connections, open circuit connection.
*	Yearly, we have a technical examination to help us improve our skills in electrical wirings. I managed to pass those examinations although they are in Japanese.
*	Overall, I learned the Japanese way of project management of a huge project while working here.

### JULY 2013 – JULY 2015
### TUTOR, MATHHUB TUTORIALS AND REVIEW CENTER
As a part-time tutor, I helped my students understand complicated concepts in Mathematics. I teach mainly high school and elementary students and sometimes freshmen college students.

## EDUCATION
### JUNE 2008 – JUNE 2015
### BS ELECTRONICS AND COMMUNICATIONS ENGINEER, UNIVERSITY OF THE PHILIPPINES DILIMAN
*	Graduated Cum laude with a Cumulative Weighted Average of 1.53 (1.00 highest)
*	Consistent Dean’s Lister
*	Specialized in designing and developing AC-DC, DC-DC power electronics.
*	My final project is a 1.5KV low power DC-DC flyback converter whose application is for a separator leakage tester in a battery manufacturing plant (the company I worked during my internship).
*	I started learning programming only in College. Most of our projects are written in C.
*	Some of my hardware, software programming course works include:
1. Designing a CPU in Quartus.
2. Creating a calculator following the IEEE 754 float arithmetic guidelines. This project is written in Assembly language
3. Creating a data logger using DHT11 temperature and humidity sensor, LDR photo sensor. The data is stored through an EEPROM, data can be viewed using an LCD. The user can provide input through keypad. All the devices are controlled by a PIC32 microcontroller.
4. Created a PID controller for a temperature-controlled environment.
5. Created a dimmer of incandescent lamp by modulating the firing angle of a TRIAC.
6. Creating a variable frequency analog signal generator (generating sine, square, triangular and saw-tooth waves) using pure BJT and MOSFET components (no OP Amps allowed).
7. Creating a loud speaker-based weighing scale, using IR LED pair as sensor to the depression of the speaker’s diaphragm. The system maintains the diaphragm position, and the supplied current required to maintain that position is used to calculate the weight of the object on the speaker.
8. Developing a multiplayer card game in C programming language called Triple Triad, using GTK for the frontend. The fundamental skill in this project is socket programming using the TCP/IP protocol.


### JUNE 2004 – JUNE 2008
### HIGH SCHOOL DIPLOMA, MISAMIS OCCIDENTAL NATIONAL HIGH SCHOOL
As a High school student, I excel in most of my subjects. My favorite subjects are Mathematics, Physics and Arts. At some point, I got perfect scores in all math exams and received 100 in my quarterly report card.
*	Graduated Valedictorian in the batch of 700 high school graduates
*	Aside from having Math as my favorite subject, I also love my drafting and woodworking class, where we created floor and elevation view plans of our dream house.
*	Consistent first placer in the annual MTAP Math Challenge in our province, reached regional level earning bronze.
*	Won 2nd place in the 2007 National Math Summit in Baguio City Philippines

## ACTIVITIES
### MAY 2011 – MAY 2013
### FULL-TIME MISSIONARY, THE CHURCH OF JESUS CHRIST OF LATTER-DAY SAINTS
In 2011, I decided to forgo my college for two years to render service in the Philippines by working as a full-time missionary.
*	Rendered community service in some areas of Butuan, and Surigao, Philippines
*	Served in various leadership roles such as being a Trainer, District Leader, Zone Leader, and lastly as Assistant to the Mission President

### JUNE 2009 – MAY 2011
### UP PROGRAMMING GUILD, UNIVERSITY OF THE PHILIPPINES
Underwent training in competitive programming. Learned about the fundamental programming algorithms. Solved math and programming problems in Project Euler (https://projecteuler.net).
