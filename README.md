# ⚡ Electric Vehicle Data Analysis

> Interactive data visualizations exploring the electric vehicle ecosystem in India, powered by Tableau and Flask.

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](http://keshu.pythonanywhere.com)
[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Flask](https://img.shields.io/badge/flask-3.0.0-lightgrey.svg)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 🚗 What is this?

Ever wondered about the state of electric vehicles in India? This project dives deep into EV datasets to uncover insights about adoption patterns, charging infrastructure, battery performance, and vehicle efficiency.

The analysis is presented through **interactive Tableau dashboards** embedded in a clean, responsive Flask web application. Explore the data, discover trends, and understand the EV landscape—all through your browser.

## 🎯 Live Demo

**🌐 Web App:** [keshu.pythonanywhere.com](http://keshu.pythonanywhere.com)

**📊 Tableau Public:**
- [Dashboard](https://public.tableau.com/app/profile/kushagra.verma4013/viz/Book2_17729068481180/Dashboard1)
- [Data Story](https://public.tableau.com/app/profile/kushagra.verma4013/viz/Book2_17729068481180/StoryofElelcticCarsinIndia)

## ✨ Features

- **Interactive Dashboards** – Filter, explore, and analyze EV data dynamically
- **Guided Data Story** – Follow a narrative through key insights and trends
- **Clean UI** – Professional black & white design with smooth animations
- **Responsive Design** – Works seamlessly on desktop and mobile
- **Easy Navigation** – Simple three-page structure for intuitive exploration

## 🔍 Key Insights

Through this analysis, you'll discover:

- 🔋 How battery capacity correlates with driving range
- 🗺️ Where charging infrastructure is concentrated (hint: urban areas)
- 📈 Efficiency variations across different EV models
- 💰 Which budget-friendly EVs offer the best range and efficiency

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Backend** | Python, Flask |
| **Frontend** | HTML5, CSS3 |
| **Visualization** | Tableau Public |
| **Database** | MySQL, SQL |
| **Deployment** | PythonAnywhere |

## 📁 Project Structure

```
Electric_Vehicle_Data_Analysis/
│
├── app.py                    # Flask application
├── requirements.txt          # Python dependencies
├── wsgi.py                  # WSGI configuration for deployment
├── README.md                # You are here!
│
├── templates/               # HTML templates
│   ├── index.html          # Landing page
│   ├── dashboard.html      # Dashboard viewer
│   └── story.html          # Story viewer
│
└── static/                  # Static assets
    └── css/
        └── style.css       # Styling and animations
```

## 🚀 Running Locally

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/IndicKangaroo/Electric_Vehicle_Data_Analysis.git
   cd Electric_Vehicle_Data_Analysis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   python app.py
   ```

4. **Open in your browser**
   ```
   http://localhost:5000
   ```

That's it! The app should now be running locally.

## 🌐 Deployment

This project is deployed on **PythonAnywhere**. To deploy your own instance:

1. Sign up at [pythonanywhere.com](https://www.pythonanywhere.com)
2. Upload your project files
3. Configure the WSGI file with your project path
4. Set up static files mapping
5. Reload your web app

For detailed deployment instructions, check out the `PYTHONANYWHERE_DEPLOYMENT.md` guide in the repository.

## 📊 Data Sources

The analysis uses publicly available datasets on:
- Electric vehicle models and specifications
- Charging station locations and infrastructure
- Battery performance metrics
- EV adoption statistics in India

All visualizations were created in Tableau Public and embedded into the Flask application for interactive exploration.

## 🎨 Design Philosophy

The UI follows a minimalist, professional design approach:
- **Black & white color scheme** for clarity and focus
- **Smooth animations** for enhanced user experience
- **Clean typography** for readability
- **Responsive layout** for all screen sizes

## 🤔 Why This Project?

Electric vehicles are the future of transportation, and India is rapidly expanding its EV ecosystem. This project demonstrates how **data visualization can make complex datasets accessible and actionable**.

Whether you're a policy maker, researcher, EV enthusiast, or just curious about sustainable transportation, these visualizations provide valuable insights into the EV landscape.

## 📝 Future Enhancements

- [ ] Add real-time charging station availability
- [ ] Include cost comparison analysis
- [ ] Integrate government incentive data
- [ ] Add predictive models for EV adoption trends
- [ ] Multi-language support

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/IndicKangaroo/Electric_Vehicle_Data_Analysis/issues).

## 📧 Contact

**Kushagra Verma**

- GitHub: [@IndicKangaroo](https://github.com/IndicKangaroo)
- Tableau Public: [Profile](https://public.tableau.com/app/profile/kushagra.verma4013)


<div align="center">

**⭐ Star this repo if you found it helpful!**



</div>