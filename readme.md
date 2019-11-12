# Projects

> Below you will find a list of my open-source projects grouped by category and language. Most of these were written as a way to learn various languages and technologies.

# Full Stack

## [Social Study](https://github.com/Social-Study/social-study)

A collaborative learning application for students of all ages. Provides essential student functionality in a central connected location. Students create "Study Groups" that relate to a specific class. Within each Study Group users can take notes, create flashcards, keep track of events, take quizzes, and chat with each other. Implemented using Vue.js and storing data and user info via Firebase. Firebase enables real-time updates to Study Group data as members add and change things. Micro-server written in Node.js / Express to convert markdown text into PDF. Written as part of my Senior Year capstone project. I was the lead developer on a time of 3 other students. The project was selected by Kutztown University for internal use and further implementation.

## [OpenBooks](https://github.com/evan-buss/openbooks)

A free eBook downloading utility that provides a simple and clean interface for searching and downloading files from `irc.irchighway.net`. Front-end written in React / JavaScript. Golang backend. Custom implemented IRC and DCC clients. Websocket communication via JSON messages to front-end user interface. Also provides an alternative CLI alternative to the web interface.

## [Family Shop](https://github.com/evan-buss/family-shop)

A collaborative shopping list mobile app for families. Create custom lists that are shared amongst all members of your family. Mobile app written in Dart using the Flutter mobile framework. Backend REST API written in Java using the Spring Boot Framework. User authentication via JSON web tokens. Data persistance via PostgreSQL. Backend deployed within a Docker container.

## [Book Keeper ](https://github.com/evan-buss/book-keeper)

The original book keeping application written when I was first learning modern web development. Provides a simple way to keep track of read books and their ratings and reviews. Written in Vue.js and Bulma CSS. Persists data and gets realtime updates via Firebase.

# Desktop

## [Web Scraping Utility](https://github.com/evan-buss/web-scraper)

Flexible and customizable web scraper written in Java using JavaFX for the GUI. Tweakable crawler settings along with customizable data retrieval rules implemented via a JSON protocol. Crawler path visualization is shown via a graph structure. Permits a greater understanding of the crawler's path and scraped data.

## [Remote Queue](https://github.com/evan-buss/remote-queue)

A desktop and mobile application to accept game queues while away from the computer. Customizable for any desktop game. Mobile app written in Dart using the Flutter mobile framework. App scans the local network for open remote-queue server instances. The desktop application is written in Node.js and uses express and websockets to enable real-time communication with the mobile app. Desktop GUI uses the Electron desktop app framework to allow cross OS compatibility.

## [Yin-Yang](https://github.com/evan-buss/Yin-Yang)

Desktop application written for the Elementary OS linux operating system. Provides an extensible and simple way to switch various app and code editor themes with the click of a button or on a set schedule. Written in the Vala programming language and using the GTK desktop UI toolkit.

## [Juliana's Catering](https://github.com/evan-buss/CSC243-JavaFX-Catering-App) 

Desktop application written in JavaFX. Makes use of the MVC pattern to separate application conerns. Provides a catering business mock application that allows users to place orders and schedule appointments. Persists data to an SQLite3 database. Final project of Java Programming class. 

# Mobile

## [Race Timer](https://github.com/evan-buss/race-timer)

A velodrome race start timer. Written in Dart using the Flutter framework. Works on both IOS and Android. Written for my brother who wanted an accurate and simple race timer for practicing his race starts. Mimics the look and sounds of the real velodrom timing system.

## [Book Keeper Mobile](https://github.com/evan-buss/book-keeper-ionic)

A cross-platform mobile app implementation of my previous Book-Keeper Vue.js single page application. Written using the Ionic hybrid mobile development framework. App written using Angular, Typescript, and Firebase. Makes use of the mobile device's native camera and local notifaction functionality. Provides a native look on both Android and IOS.

# Miscellaneous

## [NetScanner](https://github.com/evan-buss/netscanner)

A simple CLI to scan computers for open ports. Scan a single computer on all ports or scan all computers on a network for a specific open port. Fast and multithreaded.

## [Go-Serve](https://github.com/evan-buss/go-serve)

A local file server written in Golang. Allows you to share files and folders across different computers on a local network. Unlike traditional file server CLIs, it allows folders to be downloaded by compressing them into *.zip file.

## [Gitignore](https://github.com/evan-buss/gitignore)

A `.gitignore` file generation CLI utility written in Golang. Support for hundreds of languages and frameworks. If the language templates aren't specific enough, you can write custom rules to suit your needs. Used for all my projects to generate base .gitignore files

## [Font Switcher](https://github.com/evan-buss/font-switcher)

A plugin for Visual Studio Code. Enables users to quickly switch their editor font from the commmand pallete (Ctrl + Shift + P). Over 12,000 installs.

## [IMDB Web Scraper](https://github.com/evan-buss/imdb-web-scraper)

A web scraper written in Python using Scrapy. Crawls and scrapes movie data from IMDB.com. Data is stored in an SQLite3 database. Frontend data visualization via a Flask server allows you to search through the movie results and view scraped data. This served as the inspiration for writing my own web scraper implementation in Java.

## [Download Server / Client](https://github.com/evan-buss/download-server-client)

A custom download server and client CLI written in Java. Makes use of TCP sockets and multithreading. Implements a custom network protocol that enables multiple clients to traverse the server's file system and download any files they choose. Final project for my Network Programming class. 

## [Java HTTP Server](https://github.com/evan-buss/java-http)

A basic implementation of the HTTP protocol in Java. Written without the use of the Java HTTP package. Simply uses TCP sockets. All data parsing and routing is custom. Written as a way to further understand how higher-level HTTP servers work behind the scenes.

# In Progress

## Movie Streaming Application

Privately stream a movie with friends with a real-time chat.

# Future Project Ideas

## Podcast App / Website

My favorite podcast application PocketCasts recently changed their payment model from a one-time fee to monthly subscriptions. I am really not happy with it. My ideal podcast application would enable users to listen on both desktop and mobile. Podcast progress should be synced between devices. I am leaning towards a self-hosted data solution where users store their individual data in an SQLite database within their Google Drive or other cloud provider account. Mobile app in Flutter or React native. Backend services written in Java or Golang.
