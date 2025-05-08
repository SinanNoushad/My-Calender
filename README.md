# 📅 React Calendar Website

A responsive and user-friendly calendar web application built using **React**. This project displays events loaded from a static JSON file and offers a clean UI to navigate through dates.

---

## 🌐 Live Demo

🔗 [View Live Website](https://sinannoushad.netlify.app/)

---

## ✨ Features

- 📆 Day,Week,Monthly Calendar View  
- 📁 Events and tasks loaded from a **static JSON file** and **form**  
- 🗓️ Navigate Between Months  
- 🖥️ Clean and Responsive UI  
- ⚛️ Built with React  

---

## 🛠 Tech Stack

- **Framework**: React.js  
- **Styling**: CSS / Tailwind / Styled-Components  
- **Data Source**: `events.json` , `tasks.json` (Static File)

---

## 📁 Static JSON Example

Here’s an example of the `events.json` file used to load events:

```json
[
    {
      "id": 1,
      "date": "2023-05-08",
      "startTime": "10:00",
      "endTime": "11:30",
      "color": "#4285f4",
      "title": "Team Meeting",
      "location": "Conference Room A",
      "hasVideoLink": true
    },
    {
      "id": 2,
      "date": "2023-05-08",
      "startTime": "14:00",
      "endTime": "15:30",
      "color": "#ea4335",
      "title": "Project Review",
      "hasVideoLink": false
    }
]


