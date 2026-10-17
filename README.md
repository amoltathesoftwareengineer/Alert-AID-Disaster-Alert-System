# Alert-AID – AI-Powered Disaster Alert System

An AI-assisted disaster information platform designed to support hazard reporting, incident monitoring, and timely risk communication.

## Overview

Alert-AID organizes disaster-related reports and presents relevant incident information to support awareness and preparedness.

The system can classify incoming reports, summarize incident descriptions, display reported locations, and issue configured notifications when suitable alert sources are available.

It is intended as a supplementary information tool and does not replace official emergency alerts or emergency services.

## Key Features

- Disaster and hazard report management
- Incident classification
- Location-based incident visualization
- Configurable risk categories
- Incident summaries
- Notification workflow
- Incident status tracking
- Administrative review
- Historical incident dashboard

## Technology Stack

- Python
- Flask or FastAPI
- Pandas
- Scikit-learn, if a trained classification model is implemented
- Leaflet or another mapping library
- SQLite or PostgreSQL
- HTML, CSS, and JavaScript

## Project Workflow

Incident Input → Validation → Classification → Risk Review → Map and Dashboard → Configured Notification

## Project Structure

```text
Alert-AID-Disaster-Alert-System/
├── app.py
├── requirements.txt
├── README.md
├── src/
│   ├── data_validation.py
│   ├── incident_classifier.py
│   ├── risk_assessment.py
│   └── notification_service.py
├── templates/
├── static/
├── data/
└── tests/
```

## Installation

```bash
git clone https://github.com/amoltathesoftwareengineer/Alert-AID-Disaster-Alert-System.git
cd Alert-AID-Disaster-Alert-System
python -m venv .venv
```

Activate on Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Configure required environment variables and data sources before launching the implemented application.

## Run the Application

For a Flask implementation:

```bash
python app.py
```

For a configured Streamlit implementation, use:

```bash
streamlit run app.py
```

Choose the command that matches the actual application architecture.

## Safety and Reliability

- Clearly distinguish verified alerts from unverified reports.
- Show source and timestamp information where available.
- Avoid claiming that a prediction confirms an actual disaster.
- Validate notification recipients and prevent duplicate alerts.
- Protect location and personal information.
- Do not represent the application as an official emergency alert service without authorization.

## Future Enhancements

- Weather and sensor data integration
- Geospatial risk dashboards
- Multilingual alert summaries
- Offline-friendly incident reporting
- Notification delivery monitoring
- Historical hazard analysis

## Author

Amol Tathe

GitHub: https://github.com/amoltathesoftwareengineer

## License

Add an appropriate open-source license before permitting reuse.
