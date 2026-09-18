# 📊 Habit Tracker

A simple Habit Tracker built with Python and the Pixela API. The project creates a personal graph that can be used to track habits such as study time and visualize progress over time.

## 📖 Overview

This project uses the **Pixela API** to create a habit-tracking graph.

The Python program connects to Pixela using the `requests` library and sets up a user account with authentication details. It then creates a graph called **Study Graph**, where study time can be recorded in hours.

The graph is configured to store floating-point values, which makes it possible to track values such as `1.5`, `2.0`, or `3.5` hours instead of only whole numbers.

This project was built to practice working with APIs, sending HTTP requests, handling API authentication, and creating data visualizations through an external service.

## ✨ Features

- 📊 Creates a habit-tracking graph
- 📚 Designed for tracking study time
- ⏱️ Tracks values in hours
- 🔢 Supports decimal values
- 🔐 Uses API token authentication
- 🌐 Integrates with the Pixela API
- 🐍 Built using Python
- 📈 Provides a visual way to track progress

## 🛠️ Technologies Used

- Python 3
- Requests
- Pixela API
- REST API
- JSON
- API Authentication

## 📂 Project Structure

```text
Habit-Tracker/
│
├── main.py
└── README.md
Graph ID: graph1
Name: Study Graph
Unit: hours
Type: float
Color: ajisai
