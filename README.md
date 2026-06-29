# API Performance Monitor

## 📌 Overview
API Performance Monitor is a Python-based application that monitors the performance of REST APIs. It measures response time, status codes, availability, and logs performance metrics for analysis. This tool helps developers identify slow or failing APIs and monitor system reliability.

---

## ✨ Features

- Monitor one or multiple REST APIs
- Measure API response time
- Check HTTP status codes
- Log API performance data
- Store monitoring results in SQLite
- Generate performance reports
- Easy to configure and extend

---

## 🛠️ Technologies Used

- Python 3
- Flask (Optional for Web Dashboard)
- Requests
- SQLite
- Pandas
- Matplotlib (for graphs)
- Schedule (for periodic monitoring)

---

## 📁 Project Structure

```
API_Performance_Monitor/
│
├── app.py
├── monitor.py
├── database.py
├── config.py
├── requirements.txt
├── performance.db
├── logs/
├── templates/
├── static/
└── README.md
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/API_Performance_Monitor.git
```

Move into the project folder

```bash
cd API_Performance_Monitor
```

Create virtual environment

```bash
python -m venv venv
```

Activate virtual environment

### Windows

```bash
venv\Scripts\activate
```

### Mac/Linux

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python app.py
```

or

```bash
python monitor.py
```

---

## 📊 Example Output

```
API: https://api.example.com

Status Code : 200
Response Time : 245 ms
Availability : Online
```

---

## 📈 Future Improvements

- Email alerts
- Slack notifications
- Docker support
- Grafana Dashboard
- Multi-threaded monitoring
- Authentication support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Shrimayee Pattanaik**

GitHub: https://github.com/yourusername
