# wildlife-tracking

This application allows the user to add new animals to the current wild-life database. It allows users to save sightings of both endangered and normal animals. 

## Getting Started
create database using: 
*CREATE DATABASE wildlife_tracker;
*\c wildlife_tracker;
*CREATE TABLE animals (id serial PRIMARY KEY, name varchar);
*CREATE TABLE endangered_animals (id serial PRIMARY KEY, name varchar, health varchar, age varchar);
*CREATE TABLE sightings (id serial PRIMARY KEY, animal_id int, location varchar, ranger_name varchar);
*CREATE DATABASE wildlife_tracker_test WITH TEMPLATE wildlife_tracker;


## Deployment

Deployed using Heroku

## Built With

* [Maven](https://maven.apache.org/) - Dependency Management
* [Spark](https://sparkjava.com)- web framework


## Authors

Albina Nyawira Muturi


## Acknowledgments

* Hat tip to my TM Abdulfatah Mohamed, my Ace card: George Stephen Wangui
* Inspiration, youtube
* etc
