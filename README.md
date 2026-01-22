# 🔍 GitHub User Finder

A clean and responsive web application that allows users to search for GitHub profiles using the **GitHub REST API**.  
Built with **HTML, CSS, and Vanilla JavaScript**, this project demonstrates API integration, asynchronous data fetching, and dynamic DOM manipulation.

---

## 🚀 Features

- 🔎 Search GitHub users by username
- 👤 Display detailed user profile information:
  - Avatar image
  - Username
  - GitHub profile link
  - Public repositories count
  - Followers and following
  - Bio and location (when available)
- ⚠️ Graceful handling of invalid or non-existing usernames
- ⚡ Real-time data fetching using Fetch API
- 🔄 Dynamic UI updates without page reload
- 📱 Fully responsive design

---

## 🧠 Application Workflow

1. User enters a GitHub username.
2. A request is sent to the GitHub REST API:
   ```
   https://api.github.com/users/{username}
   ```
3. The API returns user data in JSON format.
4. Required fields are extracted and rendered dynamically.
5. If the user is not found, an error message is displayed.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|----------|---------|
| HTML5 | Application structure |
| CSS3 | Styling and layout |
| JavaScript (ES6) | Core logic and DOM manipulation |
| Fetch API | HTTP requests |
| GitHub REST API | User data source |

---

## 📁 Project Structure

```
Github-User-Finder
│
├── index.html      # Main UI
├── style.css       # Styling and responsiveness
├── script.js       # API logic and DOM handling
└── README.md       # Documentation
```

---

## ⚙️ Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Deep-Kacha/Github-User-Finder.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Github-User-Finder
   ```

3. Run the application:
   - Open `index.html` in any modern browser  
   *(No server or build tools required)*

---

## 📌 API Details

- **Endpoint**
  ```
  GET https://api.github.com/users/{username}
  ```

- **Data Used**
  - `login`
  - `avatar_url`
  - `html_url`
  - `public_repos`
  - `followers`
  - `following`
  - `bio`
  - `location`

⚠️ GitHub allows **60 unauthenticated requests per hour**.

---

## 🧩 Future Enhancements

- Display user repositories
- Add GitHub API authentication
- Implement loading indicators
- Add dark/light theme toggle
- Improve error handling and validation

---

## 👨‍💻 Author

**Deep Kacha**  
Entry-level software developer with practical experience in building clean, scalable, and maintainable web applications.

GitHub: https://github.com/Deep-Kacha
