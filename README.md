# Skyscanner Microservice - Hoen Scanner

A Java microservice built with the Dropwizard framework for the Skyscanner Software Engineering task.

## Overview
This microservice allows users to search for hotels and rental cars in cities of the Hoen Archipelago. It accepts JSON POST requests and returns matching results from the dataset.

## Technologies Used
- Java (OpenJDK 19)
- Dropwizard Framework
- Jackson (JSON serialisation/deserialisation)
- Maven

## Project Structure
- `Search.java` - Represents a user search request
- `SearchResult.java` - Represents a search result (hotel or rental car)
- `SearchResource.java` - REST endpoint at /search
- `HoenScannerApplication.java` - Main application class
- `HoenScannerConfiguration.java` - Dropwizard configuration

## How to Run
1. Open the project in IntelliJ IDEA
2. Click the green Run button
3. The server starts at `localhost:8080`

## How to Test
Send a POST request to `localhost:8080/search` with the body:
```json
