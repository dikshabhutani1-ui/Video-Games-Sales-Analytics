🎮 Interactive Video Game Sales Analytics Dashboard

Built using Python | Dash | Plotly | Pandas

📌 Overview

This project is an interactive analytics dashboard designed to explore global video game sales data. Users can analyze sales by Category (Title, Genre, Publisher, Developer, Console) and filter by Region (North America, Europe, Japan, Others, Worldwide).
The dashboard auto-updates visualizations using Dash callback functions, enabling real-time insights without manual refresh.

✨ Features

✔ Responsive dashboard built with Dash & Bootstrap
✔ Category and region filters for flexible analysis
✔ Dynamic Line Chart for sales trends
✔ Dynamic Bar Chart for Top 10 sales rankings
✔ Clean UI and fast performance
✔ Beginner-friendly and scalable code structure

🛠 Tech Stack
Component	Technology
Language	Python
UI Framework	Dash, Dash Bootstrap Components
Visualization	Plotly
Data Handling	Pandas, NumPy
📂 Project Structure
.
├── app.py
├── data/
│   └── video_game_sales.csv
├── assets/           # optional styling
└── README.md

🚀 How to Run

1️⃣ Clone the repository

git clone <your-repo-link>
cd <repo-folder>


2️⃣ Install dependencies

pip install -r requirements.txt


3️⃣ Run the dashboard

python app.py


🔗 The app will open in your browser at:

http://127.0.0.1:8050/

📊 Dataset

The dataset contains video game titles along with sales numbers across major global regions.
Columns include: Title, Publisher, Developer, Genre, Platform, NA Sales, EU Sales, JP Sales, Other Sales, Global Sales.

🔮 Future Enhancements

▸ Add forecasting model for predicting future sales
▸ Add user authentication / role based view
▸ Export charts as PDF/Excel
▸ Host on cloud (Render / AWS / Azure)

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to improve.

📧 Contact

If you have feedback or collaboration ideas, feel free to reach out!
