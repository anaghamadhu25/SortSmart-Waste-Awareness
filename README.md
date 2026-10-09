# SortSmart: Digital Waste Sorting Awareness System

SortSmart is a web application designed to promote proper household waste segregation[cite: 1]. Developed using Python and Streamlit, the system provides real-time guidance to help users classify waste into organic, recyclable, and e-waste streams[cite: 1].

## Key Features

* **Dynamic Item Search:** Employs an NLP scoring heuristic connected to live API endpoints (Wikipedia API) to classify waste items dynamically without reliance on hardcoded databases.
* **Image Classification Interface:** Enables photo uploads to extract metadata and visual properties for instant category detection[cite: 1].
* **Interactive Assessment Quiz:** Includes a 10-question evaluation module with instant feedback and explanatory breakdowns to reinforce correct segregation habits[cite: 1].
* **Community Analytics Dashboard:** Displays user accuracy metrics across primary municipal waste streams to highlight common segregation errors[cite: 1].

## Segregation Categories Supported

1. **Wet / Organic Waste (Green Bin):** Food scraps, fruit/vegetable peels, and compostable organic material.
2. **Dry Recyclable / Textile Waste (Blue Bin):** Paper, cardboard, clean glass, plastics, metals, jute, cotton, and dry fabrics.
3. **Hazardous / E-Waste (Red Bin):** Batteries, electronic accessories, chargers, and toxic household refuse.
4. **General Household Refuse (Black Bin):** Soiled materials and non-recyclable residual waste.

## Tech Stack & Libraries

* **Language:** Python[cite: 1]
* **Framework:** Streamlit[cite: 1]
* **Data & Image Handling:** Pandas, Pillow (PIL)[cite: 1]
* **API & Networking:** Requests[cite: 1]

## Local Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/SortSmart-Waste-Awareness.git](https://github.com/YOUR_GITHUB_USERNAME/SortSmart-Waste-Awareness.git)
   cd SortSmart-Waste-Awareness
2. **Install required dependencies:**
    ```bash
    pip install -r requirements.txt
3. **Run the Streamlit web application:**
    ```bash
    python -m streamlit run app.py