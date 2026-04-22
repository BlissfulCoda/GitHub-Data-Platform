# GitHub Data Platform (Containerised Full-Stack System)

[![Github Finder Demo](/README-Assets/Desktop.gif)][romie]

---

## Table of Contents
- [Overview](#overview)
- [Architecture](#architecture)
- [Technical Architecture Diagram](#technical-architecture-diagram)
- [Key Features](#key-features)
- [Engineering Decisions](#engineering-decisions)
- [Technologies Used](#technologies-used)
- [Demo](#demo)
- [Running Locally](#running-locally)

---

## Overview

A production-style full-stack application designed to explore real-world system design patterns including containerisation, reverse proxy architecture, and API performance optimisation.

This project integrates with the GitHub API to retrieve and display user data such as repositories, followers, and activity — with a focus on building a scalable and maintainable system rather than just UI features.

Full design work can be found on Behance:  
<a href="https://www.behance.net/portfolio/editor?project_id=164626013" target="_blank">
  <img src="https://img.shields.io/badge/Behance-1769ff?style=for-the-badge&logo=behance&logoColor=white" />
</a>

---

## Architecture

• Containerised multi-service architecture using Docker Compose  
• Nginx reverse proxy for routing and request handling  
• Backend API layer for aggregating and transforming GitHub API data  
• Redis caching layer to reduce latency and improve performance  
• Clear separation of concerns across frontend, backend, and infrastructure  

---

## Technical Architecture Diagram

[![Architecture Diagram](/README-Assets/TechnicalArchitectureDiagram.svg)][romie]

---

## Key Features

• Search and display GitHub user profiles and repositories  
• Real-time data retrieval from external APIs  
• Cached responses to minimise redundant API calls  
• Responsive UI across desktop and mobile  
• RESTful API layer for structured client-server communication  

---

## Engineering Decisions

• Built a forward proxy server to securely interact with third-party APIs  
• Introduced Redis caching to improve API response times and reduce load  
• Used Docker Compose to manage multi-service architecture  
• Implemented Nginx as a reverse proxy for routing and scalability  
• Structured application into isolated services for maintainability  

---

## Technologies Used

Frontend: React, TypeScript, Tailwind  
Backend: Node.js, Express  
Database / Cache: MongoDB, Redis  
Infrastructure: Docker, Nginx  

---

## Demo

[![Desktop Demo](/README-Assets/Demo.gif)][romie]

[![Mobile Demo](/README-Assets/Mobile1.gif)][romie]

---

## Running Locally

Clone the repo and ensure you have the following installed:
