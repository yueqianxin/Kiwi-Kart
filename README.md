# Kiwi-Kart
Smart Grocery Shopping & Carbon Footprint Optimizer

# Project Purpose
In a world of rising inflation and environmental concerns, Kiwi-Kart helps users make smarter shopping decisions. This web application calculates the most cost-effective and eco-friendly ways to buy groceries by analyzing price data from local stores within a user-defined radius.

# Core Functions
1. Smart Price Comparison (Saving Money)
The app provides two distinct strategies to help users save on their grocery bills:
  Itemized Lowest-Price Strategy: Scans all stores within your range (e.g., 5km) and identifies exactly which store has the absolute lowest price for each item on your list. (Best for maximum savings)
  One-Stop Shop Strategy: Calculates which single store offers the lowest total cost for your entire shopping basket. (Best for saving time)

2. Geofencing (Saving Effort)
The application respects user boundaries. It only considers stores within the travel radius you set, ensuring that a "deal" is only recommended if it is actually convenient for you to reach.

3. Eco-Friendly Tracking (Saving the Planet)
Kiwi-Kart goes beyond just pricing by integrating a Carbon Footprint Estimator:
  Users can select their mode of transport (Walking, Biking, Driving, etc.).
  The app calculates the carbon emissions for the trip based on the distance to the selected stores.
This allows users to balance their financial savings with their environmental impact.

# Tech Stack
 Backend: Python (FastAPI)
 
 Frontend: HTML, CSS, JavaScript
 
 Data Management: Pydantic for data validation and JSON for store/price storage.

# How to Run the Project
  - Navigate to the backend folder.
  - Install dependencies: pip install -r requirements.txt.
  - Run: uvicorn app.main:app --reload.
  - Simply open frontend/index.html in your web browser.
