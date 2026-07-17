# THE DAILY SCOOP
### A Newspaper-Themed News Web Application

## Project Overview

**The Daily Scoop** is a responsive news web application developed using **HTML, CSS, and JavaScript**. The application provides users with the latest news headlines from different categories in a visually appealing newspaper-inspired interface. It fetches live news using the **GNews API** through a **Cloudflare Worker Proxy**, ensuring secure API communication.

The project demonstrates front-end web development concepts, API integration, responsive web design, and dynamic content rendering.

---

## Objectives

- To develop a responsive news website.
- To fetch and display real-time news articles.
- To provide category-based news browsing.
- To implement keyword-based news searching.
- To design a unique newspaper-style user interface.
- To learn API integration using JavaScript.

---

## Features

- Live news updates
- Newspaper-themed interface
- Search news by keyword
- Category-wise news filtering
- Breaking news ticker
- Responsive design
- News article images
- Article source and publication time
- Direct link to full news articles
- Error handling and loading indicators

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure of the website |
| CSS3 | Styling and responsive layout |
| JavaScript (ES6) | Functionality and API integration |
| GNews API | Fetching live news |
| Cloudflare Worker | Secure API proxy |
| Google Fonts | Typography |

---

## Software Requirements

- Any modern web browser
  - Google Chrome
  - Microsoft Edge
  - Mozilla Firefox
- Internet connection
- Code Editor (VS Code recommended)

---

## Hardware Requirements

- Processor: Intel Core i3 or above
- RAM: 4 GB or higher
- Storage: 100 MB free space
- Internet connection

---

## Modules

### 1. Home Page
Displays the newspaper header, current date, and breaking news ticker.

### 2. Search Module
Allows users to search for news articles using keywords.

### 3. Category Module
Displays news according to selected categories such as:
- Top Stories
- World
- Business
- Technology
- Entertainment
- Sports
- Science
- Health

### 4. News Display Module
Shows news articles with:
- Image
- Title
- Description
- Source
- Published time
- Read More link

### 5. Error Handling Module
Displays user-friendly messages when news cannot be loaded or when an API error occurs.

---

## Working

1. The user opens the application.
2. The application loads the latest news automatically.
3. The user can select a news category or enter a search keyword.
4. A request is sent to the Cloudflare Worker.
5. The Worker fetches data from the GNews API.
6. The news articles are displayed as newspaper-style cards.
7. Clicking **Read Full Story** opens the original news article.

---

## Project Structure

```
Daily-Scoop/
│
├── daily-scoop.html
├── README.md
```

---

## Advantages

- User-friendly interface
- Attractive newspaper design
- Responsive on different screen sizes
- Real-time news updates
- Fast loading
- Secure API communication
- Easy to use

---

## Limitations

- Requires an internet connection.
- Depends on the availability of the GNews API.
- API request limits may apply.
- Does not store news articles offline.

---

## Future Scope

- User authentication
- Dark mode
- Bookmark favorite articles
- Multiple language support
- Country-based news filtering
- Voice search
- Offline reading
- News sharing on social media

---

## Learning Outcomes

Through this project, the following concepts were learned:

- HTML page structure
- CSS styling and responsive design
- JavaScript DOM manipulation
- Fetch API
- REST API integration
- Cloudflare Worker deployment
- Error handling
- Dynamic content rendering
- Front-end project development

---

## Conclusion

**The Daily Scoop** successfully demonstrates how modern web technologies can be combined to build a responsive and interactive news application. The project provides users with real-time news updates in a creative newspaper-themed interface while showcasing practical implementation of API integration, responsive design, and JavaScript programming.

---

## Developed By

**Greeshma Chavan**

**Course:** Bachelor of Technology (B.Tech)  
**Branch:** Computer Science Engineering (Artificial Intelligence & Machine Learning)

---

## License

This project is developed for **academic and educational purposes only**.
