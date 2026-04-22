# GitHub Data Platform (Containerised Full-Stack System)

![Github Finder Demo](/README-Assets/Desktop.gif)

---

## Overview

A production-style full-stack application designed to explore real-world system design patterns including containerisation, reverse proxy architecture, and API performance optimisation.

This project integrates with the GitHub API to retrieve and display user data such as repositories, followers, and activity — with a focus on building scalable and maintainable systems.

---

## Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/FramerMotion-black?style=for-the-badge&logo=framer&logoColor=blue)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-black?style=for-the-badge&logo=express&logoColor=white)
![REST API](https://img.shields.io/badge/REST-API-blue?style=for-the-badge)
![WebSockets](https://img.shields.io/badge/WebSockets-grey?style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-4ea94b?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=for-the-badge&logo=redis&logoColor=white)

---

### Infrastructure
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker--Compose-384d54?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Reverse Proxy](https://img.shields.io/badge/Reverse%20Proxy-Nginx-green?style=for-the-badge)
---

## Architecture

• Containerised multi-service architecture using Docker Compose  
• Nginx reverse proxy routing traffic between frontend and API  
• Backend API layer aggregating GitHub data  
• Redis caching layer reducing redundant API calls  
• Isolated services (client / api / db / cache) for scalability  

---

## Technical Architecture Diagram

[![Architecture Diagram](/README-Assets/TechnicalArchitectureDiagram.svg)][romie]

---

## Key Features

• Search and display GitHub user profiles and repositories  
• Real-time API integration with GitHub  
• Cached responses to reduce latency and API load  
• Responsive UI across desktop and mobile  
• RESTful API layer for structured communication  

---

## Engineering Decisions

• Built a forward proxy server to securely interact with third-party APIs  
• Introduced Redis caching to improve performance and reduce API load  
• Used Docker Compose to orchestrate services across environments  
• Implemented Nginx as a reverse proxy for routing and scalability  
• Structured application into independent services for maintainability  

---

## Demo

[![Desktop Demo](/README-Assets/Demo.gif)][romie]

[![Mobile Demo](/README-Assets/Mobile1.gif)][romie]

---

## Running Locally

Clone the repo and ensure you have:
Node.js
npm
Docker

Run:

docker-compose up --build

## Why This Project Matters

This project demonstrates the ability to design and implement production-style systems, going beyond frontend development to focus on backend architecture, infrastructure, and performance optimisation.

It highlights how real-world applications are structured — from service orchestration and API design to caching and request routing — ensuring scalability, maintainability, and efficient data handling.
