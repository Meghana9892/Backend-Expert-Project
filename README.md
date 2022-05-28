# Backend-Expert-Project
**********************************READ ME**************************************
Step1: create database in mysql in the name of "projectdb"
Step2: deploy the project
Step3: Login to the web application 
Username: admin
password: admin
Post login
Step4: change the following in hibernate.cfg.xml in project src\main folder
from:  <property name="hbm2ddl.auto">create</property> 
to:   <property name="hbm2ddl.auto">update</property>
NOTE: create value will create the database however will drop the same once refreshed
	update value will makes changes to the existing database tables however will not create tables in Dynamic web project(as per Hibernate team from google)
Step 5: add student details, teacher details, class and subject details to view all the data tables


