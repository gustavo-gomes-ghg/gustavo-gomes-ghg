<div align="center">
  <!--<img src="https://patadadeurso.com.br/images/photo.png" width="130px">-->
  <h1>Gustavo Hattenhauer Gomes</h1>
</div>


<p align="center">
  Florianópolis/Brazil
</p>

- 🔭 I’m currently working on a system to compute water reservoir hydraulic balance
- 🌱 I’m currently learning English
- 👯 I’m looking to collaborate on data engineering project
- 💬 Ask me about ocean waves, hydroeletric power plant reservoir control, or a new remote job
- 📫 How to reach me: [Linkedin](https://www.linkedin.com/in/gustavo-hattenhauer-gomes-62b4b155/)
- ⚡ Fun fact: I love car race (F1, Nascar, any car race that is on TV ...)

## Summary
Data Engineer, Software Developer and Oceanographer. Currently I work as technology and systems manager, leading a team of 17 people and developing systems to hydrological and meteorological applications. 

I have 11 years of experience as computer developer. I have experience with web programming, mobile development, Linux administration, relational databases, data analysis, statistics, time series manipulation, matrix and specialized data manipulation, and geoprocessing.

Good communication, teamwork, problem solving instinct, proactive and determined. My biggest motivation is to encounter complex challenges. Those in which it is necessary to understand the process and know the variables to solve the problem. Nothing is impossible, because for everything there is a way to do it. 

I pass my last seven years working on a hydrological complex project with four core parts: rain data assimilation, numerical modelling, data delivery, and web tools to interpretate and analyse model results. See my work experiences listed below to best understand this project. 

I'm currently looking for a Data Engineer or Backend position, where I think I'll have my best performance.

## English Level
Currently, I am studying on Open English school. It has a course with 8 English levels. Currently I passed level 5, and I'm studying level 6 to get B2 certificate.

- 2022-May: CEFR A2
- 2022-Sep: CEFR B1

## Recent Technical Evaluation

2022-Apr: Approved on Technical test's on Turing platform:
- Javascript
- Python
- Matlab
- SQL
- Docker

2022-May: Approved on Technical test's on Turing platform:
- AWS
- AWS Lambda
- Django

## Soft skills
I don't have attention deficit, I know how to work in a team, I try to understand the problem I'm trying to solve, easy to learn new tools and new programming languages, fast learning curve, quick thinking, while in a meeting I quickly design the workflow and process being discussed (this makes it much easier for other team members to understand), ease of having an idea to solve a problem, I don't waste my time and other colleagues' time talking more than necessary, if I don't have anything to say I don't interrupt conversations, sincerity(if I don't know how to do something I say I don't know).

- I organize my time using personal calendar (Teams, Outlook, Google).

## Positives/Negatives
- Positives: good character, good relationship with the team, ability to simplify complex problems, agile and practical.
- Negatives: I try to quickly solve a problem and being quick may not be the best solution, impatient, difficulty not showing displeasure.

## Education
- _Cybersecurity and Ethical Hacking (Graduate course), UNICIV_ -> Mar 2021 - Feb 2022, Remote
#####
- _Software Engineering (Graduate course), UNYLEYA_ -> Jul 2020 - Jun 2021, Remote
#####
- _Oceanography (Undergraduate course), UNIVALI_ -> Jan 2005 - Jun 2010, Itajaí- Santa Catarina - Brazil

## Work History

#### Technology Manager
_Fractal Engenharia, Florianópolis/SC/Brazil_
_(On-site/Remote) -> Jun-2019 - Present_

#### Data Engineer
_Fractal Engenharia, Florianópolis/SC/Brazil_
_(On-site/Remote) -> Apr-2015 - Present_

#### Web Developer
_Fractal Engenharia, Florianópolis/SC/Brazil_
_(On-site/Remote) -> Apr-2017 - Present_

#### Android Developer
_Fractal Engenharia, Florianópolis/SC/Brazil_
_(On-site/Remote) -> Apr-2017 - Present_

#### Oceanographer
_Chigago Bridge & Iron, Florianópolis/SC/Brazil_
_(On-site) -> 2012-2018_

#### GIS Analyst
_Caruso Jr, Florianópolis/SC/Brazil_
_(On-site) -> 2011-2012_

#### Support (Geoprocessing and Remote Sensing)
_Universidade do Vale do Itajaí, Itajaí/SC/Brazil_
_(On-site) -> 2010-2011_

#
## Projects

### GHG Twitter Stream Messaging Tracker - Apache Kafka, Apache Spark, NodeJS
_GHG Tecnologia -> May-2022 - Present_
###
##### _Project Overview_
A personal project to learn how to use Apache Kafka main features, Apache Spark to process stream data, NodeJS as backend to Kafka Producers and Consumers, and Twitter Stream API rules to get specific tweets using stream data.

This project outlines 4 main interest areas (Outer Space/Universe, Car racing, Games news and Data Engineering news), and 4 different repositories.
The data pipeline is separated in a) data ingestion layer using Twitter Stream API, saving data on Apache Kafka, b) a Speed Layer for compute analytics from stream messages, and c) a Visualization layer to display messages and analytics.

  - a) Data ingestion layer uses NodeJS as backend and KafkaJS library as external client to act as Kafka Producer and Consumer for tweets. Kafka set up with Docker image
  - b) Speed layer uses Apache Spark Python API to compute analytics and Kafka Python external client to act as analytical Producer
  - c) Visualization layer uses ReactJS to display tweets and analytics from each different topic in distinct pages. New messages and analytics are received using socket connection from backend.
![](https://github.com/gustavo-gomes-ghg/gustavo-career-history/blob/master/public/images/data_engineering/twitter_stream/twitter_stream_new.png)

##### _Learning Outcomes_
From this project I'm learning the main features of Apache Kafka, Apache Spark and Twitter API.


### Patada de Urso API using NodeJS and Sequelize
_GHG Tecnologia -> May-2022 - Present_

###
##### _Project Overview_
Porting PHP classic API to NodeJS application using Sequelize ORM library. The API project includes CRUD features for +20 endpoints, integrated with Python scripts to send emails and for creatING images to post on Instagram.

##### _Learning Outcomes_
From this project I'm learning the main features of NodeJS and Sequelize ORM.

### ETL Project - Weather forecast data ingestion to GeoServer
_Fractal Engenharia -> Jun-2022 - Present_
###
##### _Project Overview_
Weather forecast scientific grib2 data file download, rainfall precipitation data extraction, data transformation to compute analytics for matrix and for coordinate points, creation of gif animation, and geoserver upload of matrix data, json and raster images. All the data pipeline is set up on Apache Airflow DAG, using distinct tasks for Python codes, and utilizing Airflow properties to minimize issues during the data pipeline.
![](https://github.com/gustavo-gomes-ghg/gustavo-career-history/blob/master/public/images/data_engineering/geoserver/geoserver_dag.png)

### DBA maintenance in huge database
_Fractal Engenharia -> April-2022 - Present_

###
##### _Project Overview_
Database with 700GB size running out disk size space. To solve this problem, the main database was segregated in different databases, located in different servers, based on data time stamps (hot, buffer, cold). The 'buffer' database was used to store data for 3 months. After that period data is transferred to the 'cold' database and tables are cleaned. In 'hot' database are stored recent and highly queried data. Every day a routine is executed to transfer data older than Today-60 days to the 'buffer' database, and remove this data from 'hot' database. All this process was set up on Apache Airflow DAG, with distinct tasks to better track issues and give the retry option. Failed task activity is communicated to DBA using TelegramOperator.

Adaptations were necessary on application to query data from different databases and work properly again.
![](https://github.com/gustavo-gomes-ghg/gustavo-career-history/blob/master/public/images/data_engineering/dba_maintenance/dba_hotbuffer.png)
![](https://github.com/gustavo-gomes-ghg/gustavo-career-history/blob/master/public/images/data_engineering/dba_maintenance/dba_buffer_cold.png)

##### _Learning Outcomes_
From this project I'm improving my skills with PostgreSQL maintenance tools like vacuum and analyze, how to transfer data between databases performatically, how to execute maintenance processes in production without turning off the application, with less impact on database performance.

###
### Web system migration to AWS Cloud - Cybersecurity motivation
_Fractal Engenharia -> Sep-2021 - Mar-2022_

Project: [SIG²A](https://siga.fractaleng.com.br)

**Web system migration from Linode cloud to AWS cloud.**

###
##### _Project Overview_
A customer and your TI team have analyzed the system and has suggests several improvements, either cybersecurity as infrastruct. After our analyse, we decide that the best choice was to migrate to AWS cloud and setup AWS services to specific purposes.

We worked is six different areas:
- User authentication and data security improvements. The solution was integrate an authentication system that comprised: multi-factor authentication, password policy, password change after perior, account lockout after attempts;
- Periodic vulnerability assesment to find weakness and flaws on system;
- Traffic inspection and web application firewall (WAF);
- Proper isolation of application (web server, database, app server);
- Data-at-rest encryptation to protect customer data;
- Business Continuity and Disaster Recovery Plan to minimize downtime in case of failure.

Currently this project has been completed and is in production. All services are working properly.

##### _Learning Outcomes_
From this project, I learned a such AWS services features and how it works. On the technical side, about AWS services, I learned about costs and how optimize, setup of security groups rules, how to encrypt existing EBS volumes properly, ALB and WAF setup, features and rules, Buckets and users security.
I also strengthened my skills involving clouding services and application, encouraging me to migrate another applications or to start a new project with a serverless approach.

Regarding project management, I also learned how to think about and make right choices to avoid that your project stay sticked to a specific cloud forever.

<div align="center">
  <img alt="infrastructure" src="https://patadadeurso.com.br/images/infrastructure/infra.png" width="500px">
</div>

#
### DAMS App
_Fractal Engenharia -> April-2017 - Present_

Project: [DAMS](https://fractaleng.com.br/solucoes/dams/) 

Google Play: https://play.google.com/store/apps/details?id=com.fractalengenharia.DamsApp

**Dam safety Android app for manually monitoring auscultation instruments in hydropower and mining dams.**
###
##### _Project Overview_
Is a engineering project created to monitoring dams auscultation instruments and perform dam structures visual inspection. The app is able to execute a complete auscultation cycle, registering different information about instruments. The main features are: instrument identification by QR Code, reader person name, instrument readings with confirmation, the app works offline saving data in internal smartphone/tablet database (SQLite), take site/field photos, observations, occurrences and instrument maintenance request registers.
The same app is able to execute 'Visual Inspection' of dams, based on form created on SIG²A. The engineer can register structures conditions in site, take photos, and sent information to SIG²A. After auscultation or visual inspection service is completed, all data are sent to web platform (SIG²A) and several PDF reports are generated.

This project was built using Android Studio platform and Java language. The user data is stored using SQLite database. API endpoints from PHP + Symfony Framework.

This project is in production. Currently we have contract with 6 great energy generator groups, monitoring 13 hydro eletric dams, including large, medium and small dimensions dams. Every month more than 1660 auscultation instruments are read at least one time.

##### _Learning Outcomes_
From this project I learned to work with Android SDK advanced properties, like ReciclerView, BaseAdapter, SurfaceHolder, SurfaceView, Fragments, sharedPreferences, SQLite database to internal storage, parsing GPS coordinates, listeners, Volley library to Rest API calls, Gradle packages manager, Android code security and key store, Google Play app publish on alfa, beta and production channels, Google Play account management when Google had required code adjusts and credential's do access app and keep it on Google Play, app optimization and code tests in different devices with different screen sizes, modify and evolve code to works on newer Android versions (this app was launched when last Android version was 5 - Lollipop. Actually was on 11 - Red Velvet Cake), among others learnings.
It is also worth mentioning about learnings in project files organization, both logic as layouts (for different screen sizes), and also about code internalization with tags for different languages.

DAMS  |  App  |  screen  |  shots
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](https://patadadeurso.com.br/images/dams/dams_01.png) | ![](https://patadadeurso.com.br/images/dams/dams_02.png) | ![](https://patadadeurso.com.br/images/dams/dams_03.png) | ![](https://patadadeurso.com.br/images/dams/dams_04.png)
![](https://patadadeurso.com.br/images/dams/dams_05.png) | ![](https://patadadeurso.com.br/images/dams/dams_06.png) | ![](https://patadadeurso.com.br/images/dams/dams_07.png) | ![](https://patadadeurso.com.br/images/dams/dams_15.png)
![](https://patadadeurso.com.br/images/dams/dams_16.png) | ![](https://patadadeurso.com.br/images/dams/dams_18.png) | ![](https://patadadeurso.com.br/images/dams/dams_19.png) | ![](https://patadadeurso.com.br/images/dams/dams_20.png)

#
### DAMS Auscultation Campaign Validation Report - Python
_Fractal Engenharia -> Feb-2019 - Apr-2019_

###
##### _Project Overview_
...
##### _Learning outcomes_

#
### AngularJS web platform
_Fractal Engenharia -> April-2017 - Present_

Project: [SIG²A](https://www.fractaleng.com.br/SIGA/user_guide/user/) 


**Modular Single Page application with tools for dam safety, hydrology monitoring and hydrology forecast system.**
Written in AngularJS, and currently in migration to ReactJS with Single SPA library. Backend with PHP Symfony Framework, and Python Django Framework.

###
##### _Project Overview_
SIG²A is a complete web solution to customers visualizing your data, make analysis and to register information about dam security, hydrological river monitoring and river flow predictions to hydroeletric power stations. SIG²A is integrated with DAMS App, SPEHC and RESOP products.

The project is a modular single page application, based on API restful, written in AngularJS and actually in migration to ReactJS with Single-SPA library. Backend is provided by two different projects, as PHP + Symfony Framework, and Python + Django Framework.

Hosted on AWS, has Auth0 authentication service and Business Continuity and Disaster Recovery Plan available.

The project architecture was idealized and developed by me. Currently the platform has 33 modules and I can maintain all them, either JavaScript logic or CSS style. Each module can be considered a different project because its business logic is in Frontend side, written in JavaScript. The most advanced tools comprising numerical calculations and show instruments time series data on graph and spatial information on maps.

SIG²A was built with a version control guideline documentation and every new pull request made, the developer who work on it need to add version description and versioning number.

#### _Learning outcomes_
From this project, and because is a long project, I learned a lot of things. On technical side, I learned how to work properly with a single page application project, best pratices of web programming, javascript and ES6 new features, AngularJS tricks and how to solve problems, how to work with Material Desing library and to explore its html/css features properly, and so on. Because AngularJS large files characteristic, I needed to integrate a lazy loading library to charge static files only when necessary to mantain the best user experience. I also streghtened my skills with git versioning, deploy pipelines and dev/stage/production environments.
Regarding project management, I learned how to work with developers who not want to work with a specific framework (AngularJS is deprecated since 2018). I learned also how to break down tasks within a module into smaller incremental steps. 

SIG²A  |  Web platform
:-------------------------:|:-------------------------:
![](https://patadadeurso.com.br/images/siga_web_platform/siga_01.png) | ![](https://patadadeurso.com.br/images/siga_web_platform/siga_01.png)
![](https://patadadeurso.com.br/images/siga_web_platform/siga_03.png) | ![](https://patadadeurso.com.br/images/siga_web_platform/siga_04.png)
![](https://patadadeurso.com.br/images/siga_web_platform/siga_05.png) | ![](https://patadadeurso.com.br/images/siga_web_platform/siga_06.png)
![](https://patadadeurso.com.br/images/siga_web_platform/siga_07.png) | ![](https://patadadeurso.com.br/images/siga_web_platform/siga_08.png)
![](https://patadadeurso.com.br/images/siga_web_platform/siga_09.png) | ![](https://patadadeurso.com.br/images/siga_web_platform/siga_10.png)
![](https://patadadeurso.com.br/images/siga_web_platform/siga_11.png) | ![](https://patadadeurso.com.br/images/siga_web_platform/siga_12.png)
![](https://patadadeurso.com.br/images/siga_web_platform/siga_13.png) | ![](https://patadadeurso.com.br/images/siga_web_platform/siga_14.png)
![](https://patadadeurso.com.br/images/siga_web_platform/siga_15.png) | ![](https://patadadeurso.com.br/images/siga_web_platform/siga_16.png)
![](https://patadadeurso.com.br/images/siga_web_platform/siga_17.png) | ![](https://patadadeurso.com.br/images/siga_web_platform/siga_18.png)
![](https://patadadeurso.com.br/images/siga_web_platform/siga_19.png) | ![](https://patadadeurso.com.br/images/siga_web_platform/siga_20.png)

#
### Rainfall-Runoff forecast system (SPEHC)
_Fractal Engenharia -> May-2015 - Present_

Project: [SPEHC](https://fractaleng.com.br/solucoes/sistema-de-previsao-de-eventos-hidrologicos-criticos/) 


**Water resources management operational application. It predicts rivers flow based on how much it rained and how much it will rain in a watershed of interest. In 2021, a port to Python language was written.**
Written in Matlab and Python. Uses PostgreSQL database engine.

###
##### _Project Overview_
Under construction ...

##### _Learning outcomes_

#
### Weather forecast assimilation modules
_Fractal Engenharia -> May-2015 - Present_

**Development of the Telemetric Data Assimilation module from ANA Stations (National Water Agency) for the SPEHC system. Data assimilated to proprietary databases.**

###
##### _Project Overview_
Under construction ...

##### _Learning outcomes_

#
### Patada de Urso - Landing page (Wordpress)
_GHG Tecnologia -> Jan-2018 - Mai-2018_

###
##### _Project Overview_
Under construction ...

##### _Learning outcomes_

#
### Patada de Urso - AngularJS web platform
_GHG Tecnologia -> Jan-2018 - Mai-2018_

###
##### _Project Overview_
Under construction ...

##### _Learning outcomes_

#
### MetaTrader 5 - Software Developer
_GHG Tecnologia -> 2017 - Dez-2017_

**Trader robot for daytrade operations in mini-index and mini-dollar contracts using Metatrader 5 tool.**

###
##### _Project Overview_
Under construction ...

##### _Learning outcomes_


#
### Notifymer
_Personal project -> Jan 2017 - Feb 2017_

###
##### _Project Overview_
App development for Android – Notifymer – Making programmer life easier (alpha version), available on Play Store. Receive Push notifications from any code/software on your smartphone. Before the Telegram channel it was very useful.
Project link: https://play.google.com/store/apps/details?id=com.ghgtecnologia.notifymer

##### _Learning outcomes_


#
### Port Feasibility Tool
_Chigago Bridge & Iron -> Sep 2016 - Feb 2017_

###
##### _Project Overview_
Creation of the “Port Operation Regime” tool. Simulation of the operation of ships in ports – Tool developed to find the maximum number of ships that a terminal can operate over a year, changing technical and mechanical characteristics of loaders/unloaders. Tool that uses current fields output from the Delft3D hydrodynamic model, based on a conceptual ship model, navigation channel design, vessel propulsion and maneuverability characteristics, configuration of the number of mooring berths, number of mooring areas and operating time of each berth, to compute the terminal operating fee. Application for ports and port terminals.
Tool to be used in conjunction with 'Port Navigation Tool' and logistical studies, in order to study the feasibility of a port terminal, regarding the operation of ships and cargo handling.
This tool was developed to study the feasibility of the port terminal in Mearim, MA.

Requirements:
- Delft3D hydrodynamic current field
- Navigation channel
- Navigation windows from 'Port navigation tool'

##### _Learning outcomes_

#
### Port Navigation Tool
_Chigago Bridge & Iron -> Apr 2014 - Dec 2014_

###
##### _Project Overview_
Creation of “Port Navigation” tool. This tool uses current fields from the Delft3D hydrodynamic model, based on a conceptual ship model, navigation channel design, and vessel propulsion and maneuverability characteristics to find possible navigation windows during a given period of time. Application for ports and port terminals. 

##### _Learning outcomes_

#
### Low cost Tide Gauge
_Personal project -> Sep 2015 - Dec 2016_

###
##### _Project Overview_
Development of a low cost tide gauge (sea level measurement instrument). Android application development to manage the instrument via Bluetooth, enabling:
- on/off;
- receipt of measured data and processing/noise filters;
- synchronization of consolidated data with api.


##### _Learning outcomes_


#
### Wave Forecast Operational System 
_Personal project -> Sep 2015 - Jun 2016_

###
##### _Project Overview_
Development of an operational system for the execution/processing/upload and website to show WaveWatchIII wave forecast results for the Atlantic Ocean, nested with the shallow water wave prediction model SWAN for south and southeast coast of Brazil. Forecast data was then presented on a website. It is a system similar to Waves, SurfGuru, Broou, magicseaweed, surfline, etc.

##### _Learning outcomes_

#
### Delft3D-Part Automations
_Chigago Bridge & Iron -> Feb 2015 - Jun 2015_

###
##### _Project Overview_
Numerical modeling of an oil spill for Santos Bay and adjacent oceanic region. Numerical model used (Delft3D PART module). Development of a tool for automating probabilistic oil simulations using the PART-Delft3D module. Prepared for Companhia Docas of the State of São Paulo (CODESP). 

##### _Learning outcomes_

#
### Delft3D Morphological Analysis Package
_Chigago Bridge & Iron -> Feb 2014 - Jul 2014_

###
##### _Project Overview_
Creation of “Delft3D Morphological Analysis Package” tool for processing and analyzing morphological data from the Delft3D numerical model. Focus on sediment transport and analysis of beach environments with coastal works (beach nourishment, rigid structures, breakwater). Performs volume calculations and sediment transport rates for each run in Delft3D, allowing sensitivity tests and morphological calibration.


##### _Learning outcomes_

#
### Wave Extreme Analysis Tool
_Chigago Bridge & Iron -> Jan 2014 - Mai 2014_

###
##### _Project Overview_
Creation of the “Extreme Wave Data Analysis” tool for processing and analyzing extreme wave data, using several statistical models to predict Hs and desired return period. Evaluation of historical series of Hs, Tp, Dir, magnitude and wind direction. Based on the history, the payback period is calculated for each selected variable according to different methodologies (USACE, GEV, Weibull, others). The code was built on a graphical interface making it easy for the user and allowing to obtain this type of information in seconds.

##### _Learning outcomes_

#
### XBEACH GUI
_Chigago Bridge & Iron -> Jul 2013 - Dec 2013_

[Project Link](https://github.com/gustavo-gomes-ghg/xbeach_gui)

###
##### _Project Overview_
Creation of the “Xbeach GUI” graphical interface of the Xbeach Model (eXtreme Beach Behavior – Delft, Netherlands) to configure the input parameters of the numerical model. It was a graphical interface developed in Matlab during a project at CBI where we used the XBEACH model to simulate extreme event ripples. The motivation was created by the difficulty in understanding and configuring the model. From this, I created a GUI similar to the Delft3D GUI, where it is possible to modify the setup parameters and save the setup file according to the user's choices, besides being able to load a setup and the interface is updated. In addition, a module for viewing the grid and bathymetry of the model in plan was created, and a tool for calculating the shape of the beach in plan according to the parabolic model of Hsu.

##### _Learning outcomes_

##
GUI for model setup
![](https://github.com/gustavo-gomes-ghg/xbeach_gui/raw/master/assets/gif/main_gui.gif)

##
GUI - Visualization Area 1
![](https://github.com/gustavo-gomes-ghg/xbeach_gui/raw/master/assets/gif/view_analysis_1.gif)

##
GUI - Visualization Area 2 - Static Equilibrium Shoreline Analysis
![](https://github.com/gustavo-gomes-ghg/xbeach_gui/raw/master/assets/gif/view_analysis_2.gif)

##
GUI - Visualization Area 3 - Topography profile analysis
![](https://github.com/gustavo-gomes-ghg/xbeach_gui/raw/master/assets/gif/profile_analysis.gif)

##
GUI - Visualization Area 4 - Land Boundary
![](https://github.com/gustavo-gomes-ghg/xbeach_gui/raw/master/assets/gif/land_boundary.gif)

#
### Real-time AWAC
_Chigago Bridge & Iron -> Jun 2013 - Ago 2013_

###
##### _Project Overview_
Creation of software in a Matlab environment for reading and processing AWAC data (instrument deployed at the aqueous environments that measures waves and currents) in real time, from the Hydrodynamic Forcing Monitoring System in the Tubarão complex, Vitória/ES. The software received binary data through the serial port, converted it to hexadecimal, processed the information, displayed it on the screen and stored it in ASCII files. The connection cable was connected directly from the instrument to a connection box in a sheltered place where the processing was done.

##### _Learning outcomes_


<!--
**gustavo-gomes-ghg/gustavo-gomes-ghg** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
