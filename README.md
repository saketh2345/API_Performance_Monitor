#  API Performance Monitor

##  Project Overview

The **API Performance Monitor** is a Python Flask-based web application designed to monitor and analyze the performance of different API endpoints.

It measures API response time, tracks HTTP status codes, identifies failed requests, and stores performance records in an SQLite database.

The application provides a simple dashboard to view API performance statistics and recent monitoring results.

##  Features

- Monitor HTTP and HTTPS API endpoints.
- Measure API response time in milliseconds.
- Track HTTP status codes.
- Identify successful and failed API requests.
- Store API monitoring records in SQLite.
- Display total API checks.
- Calculate API success rate.
- Display average response time.
- View recent API monitoring history.
- Generate API performance summaries.
- Clear stored monitoring records.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web framework |
| Requests | Sending HTTP requests |
| SQLite | Database management |
| HTML | Dashboard structure |
| CSS | Dashboard styling |
| JavaScript | Frontend interaction |

##  Project Structure

```text
API_Performance_Monitor/
│
├── app.py
├── requirements.txt
├── README.md
│
└── templates/
    └── dashboard.html
```

**Database:** `monitor.db` is automatically created when the application initializes.

## ⚙️ Installation and Setup

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open the Project Folder

```bash
cd API_Performance_Monitor
```

### Step 3: Install Required Packages

```bash
pip install -r requirements.txt
```

### Step 4: Run the Application

```bash
python app.py
```

### Step 5: Open the Application

Open your browser and visit:

```text
http://127.0.0.1:5000
```

##  How to Use the Application

1. Start the Flask application.
2. Open the API Performance Monitor dashboard.
3. Enter an API endpoint URL.
4. Click the **Check API** button.
5. The application sends an HTTP request to the selected API.
6. Response time and HTTP status code are calculated.
7. The monitoring result is saved in the SQLite database.
8. View the updated performance statistics on the dashboard.

##  Sample APIs for Testing

You can use these free public APIs to test the application.

| API Name | API URL |
|---|---|
| JSONPlaceholder | https://jsonplaceholder.typicode.com/posts |
| GitHub API | https://api.github.com |
| DummyJSON | https://dummyjson.com/products |
| HTTPBin | https://httpbin.org/get |
| Random User API | https://randomuser.me/api/ |

##  API Endpoints

| HTTP Method | Endpoint | Description |
|---|---|---|
| POST | `/api/check` | Check API performance |
| GET | `/api/metrics` | Retrieve monitoring records |
| GET | `/api/summary` | Get performance statistics |
| POST | `/api/metrics/clear` | Clear monitoring records |

##  Performance Metrics

The application tracks the following metrics:

- **Total Requests:** Total number of API checks.
- **Successful Requests:** Number of requests with HTTP status codes from 200 to 399.
- **Failed Requests:** Number of unsuccessful requests.
- **Success Rate:** Percentage of successful requests.
- **Average Response Time:** Average time taken by APIs to respond.
- **Maximum Response Time:** Highest recorded response time.

##  Project Objectives

- Understand API monitoring and testing.
- Learn Flask web application development.
- Measure API response time.
- Analyze HTTP response status codes.
- Work with Python Requests.
- Store and retrieve data using SQLite.
- Build an interactive monitoring dashboard.

##  Future Enhancements

- Automatic API monitoring at scheduled intervals.
- Email alerts when an API fails.
- Graphical performance reports.
- API uptime tracking.
- Multiple API monitoring.
- Export monitoring reports to CSV or PDF.
- Advanced performance analytics.

##  Author

**Name:** [Enter Your Name]

**Project Name:** API Performance Monitor

**Domain:** Python Full Stack Development

**Project Type:** Internship Project



