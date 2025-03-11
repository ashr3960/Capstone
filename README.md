# Project Title
Event Management Web Application

## Overview

What is your app? Give a brief description in a couple of sentences.
A web application that allows city officials to post public events and general users to create, manage, and RSVP to private events. Users can browse public events, engage in discussions, and connect with others based on shared interests.

### Problem Space

Why is your app needed? Give any background information around any pain points or other reasons.
Many event platforms lack a community-driven approach to event discovery and engagement. City officials struggle to share public event details effectively, and private event hosts lack tools for easy guest management and RSVPs.

### User Profile

Who will use your app? How will they use it? Add any special considerations that your app must take into account.
City Officials: Post and manage public events for community awareness.
General Users: Create private events, invite guests, RSVP to events, and engage in discussions.

### Features

List the functionality that your app will include. These can be written as user stories or descriptions with related details. Do not describe _how_ these features are implemented, only _what_ needs to be implemented.

City officials can create and manage public events.
Users can create private events, invite others, and track RSVPs.
Event browsing with filtering by categories.
Community threads for event discussions and reviews.
Optional monetization for paid events.
Optional Integration with Google Calendar for scheduling.
Optional User-uploaded event images.
Direct connections between users with shared interests.

## Implementation

### Tech Stack

List technologies that will be used in your app, including any libraries to save time or provide more functionality. Be sure to research any potential limitations.

Frontend: React.js with SCSS
Backend: Node.js with Express.js
Database: mySQL

### APIs

List any external sources of data that will be used in your app.

Possibly Google Calendar API (for event syncing)
Possibly Payment API (Stripe or PayPal for ticketed events)
Possibly Image hosting API (Cloudinary for user-uploaded images)

### Sitemap

List the pages of your app with brief descriptions. You can show this visually, or write it out.

Homepage – Browse public events
Login/Register – User authentication
Event Details Page – View event info, RSVP, comment
Create Event Page – Form for creating public/private events
User Dashboard – Manage created and RSVPed events
Community Threads – Discussions around events
Admin Panel – City officials manage public events

### Mockups

Provide visuals of your app's screens. You can use pictures of hand-drawn sketches, or wireframing tools like Figma.

### Data

Describe your data and the relationships between the data points. You can show this visually using diagrams, or write it out. 

Users: (id, name, email, role, interests)
Events: (id, title, description, date, location, type, createdBy)
RSVPs: (id, userId, eventId, status)
Comments: (id, userId, eventId, content, timestamp)
Categories: (id, name)

MAY BE SUBJECT TO CHANGE

### Endpoints

List endpoints that your server will implement, including HTTP methods, parameters, and example responses.

POST /register – Register a new user
POST /login – Authenticate user
GET /events – Retrieve all public events
POST /events – Create a new event
GET /events/:id – Fetch event details
POST /events/:id/rsvp – RSVP to an event
POST /events/:id/comment – Post a comment on an event

MAY BE SUBJECT TO CHANGE

## Roadmap

Scope your project as a sprint. Break down the tasks that will need to be completed and map out timeframes for implementation working back from the capstone due date. 


---

## Future Implementations
Your project will be marked based on what you committed to in the above document. Here, you can list any additional features you may complete after the MVP of your application is built, or if you have extra time before the Capstone due date.

Optional monetization for paid events.
Optional Integration with Google Calendar for scheduling.
Optional User-uploaded event images.

