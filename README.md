# Bun Nuoc Co Le – Backend (Golang)

## Overview

This backend system was developed for Bun Nuoc Co Le restaurant during its early operational phase.
It provides RESTful APIs for both the website frontend and Android application, while handling business logic and managing restaurant data.

## Objectives

* Provide APIs to retrieve menu data for the website and manage menu data for the Android application
* Handle business logic of the system
* Manage and store data efficiently
* Ensure stable performance when deployed on low-cost cloud platforms

## Development Criteria

* Follow RESTful API design principles
* Maintain clean and well-structured code
* Ensure fast response time and optimized performance
* Design for scalability and future feature expansion
* Apply layered architecture (Controller – Service – Repository)
* Integrate with external services

## Demo

* Frontend: (https://bunnuoccole.netlify.app/): https://github.com/letan-165/family-restaurant-vanilla
* Backend (Golang API): https://github.com/letan-165/family-restaurant-golang
* Android: Internal application (private, used by the restaurant owner): https://github.com/letan-165/family-restaurant-android

## Tech Stack

* Golang
* Gin (Web framework)
* GORM (ORM)
* MongoDB Atlas (Cloud Database)
* Cloudinary (media storage and image delivery)
* Koyeb (deployment)

## Architecture

* RESTful API architecture
* Layered architecture:

  * Controller: handles HTTP requests/responses
  * Service: handles business logic
  * Repository: interacts with the database
* MongoDB is used for data storage
* Cloudinary is used for media storage and delivery
* Designed to efficiently serve multiple clients (web and mobile)

## Features

* Provide APIs to retrieve menu list
* Provide APIs to manage menu items (create, update, delete)
* Handle requests from frontend and mobile applications
* Manage image data via Cloudinary
