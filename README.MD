Rocket Source Repository
========================

Top Level Directories:
----------------------
  docs                       - Documentation for developers of Rocket Trivia.
  rocket-maintenance         - Utility scripts to help with DB administration.
  rocket-open-trivia-loader  - Scripts for downloading and formatting data from opentb.com.
  rocket-schema              - SQL for creating the database.
  rocket-service             - Web service and user interface code.

Key Documentation:
------------------
  * docs/Rocket Trivia - Web Application Documentation.docx
      This document contains the final documentation for the project.
 
  * docs/Rocket Trivia - Poster.pptx
      This is the poster used for the presentation.      

Video Documentation:
---------------------
  * https://drive.google.com/open?id=15mSQcBBpvl5548c--BY9fBm684TaqD9p

      This google drive directory contains video screen casts explaining how
      to setup the application, run it, develop on it, and test
      new features.

Important Sub-Directories:
---------------------------
  rocket-schema/init
    * Contains SQL for creating all tables.

  rocket-schema/test-data
    * Contains SQL for populating some question test data.

  rocket-service/src/main/java/rocket/controllers
    * Contains java code for implementing the REST APIs to manipulate the database.

  rocket-service/src/main/java/rocket/mappers
    * Contains all of the SQL used by java code for manipulating the database.

  rocket-service/src/main/webapp/app
    * Contains most of the user interface code for the application.
      This includes Java Script, HTML, and CSS.
    
