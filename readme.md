# Introducttion to MasterClass (Objects)

In this project you will find:
 - A Site Initializer Client Extension evolving the current MasterClass Site Initializer in Liferay DXP
 - A Batch Client Extension to create Objects as the base for Courses, Teachers, Enrollment, etc.
 - Additional Front End Client Extensions JS / CSS to complete the different use cases.
 
# Code Structure

 The code itself has two branches:
  - Main: this is the final code, that represents this example in a complete way
  - DevCon: this is a branch where part of the example is not complete so we can use this starting point as a workshop in Liferay Devcon 2024 (or you yourself, apart from Devcon at your own peace)

# Releases
 
 There's also some releases:
  - Devcon release: the same CX ZIPs but in the intermediate state to be completed during a workshop in Liferay Devcon 2024
  - Complete release Nov 2024: the different CX ZIPs already compiled to be deployed as CXs both in Cloud and SH Liferay DXP installations. 
  - I will be adding more releases as soon as I succeed in adding more features: categorization, course rating, course geolocation, seats management, etc.
 
 Please read the instructions that you'll find together with the releases' notes in order to install the CX properly if you decide to build them from the source code. In such a case, just for you to know I was using 2024.Q3.3 as my basic version configured in Liferay Workspace, etc.
 One more thing: if you are using 2024.Q3 or prior, please remember to have activated the following Feature Flag to be able to process Base64 attachments in objects: 
  - add to your potal-ext.properties --> feature.flag.LPS-174455=true
 
 Thanks! More than happy to get PRs or suggestions through rafael.lluis@liferay.com
