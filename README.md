# SortSmart: Digital Waste Sorting Awareness System

SortSmart is a web application designed to promote proper household waste segregation[cite: 1]. Developed using Python and Streamlit, the system provides real-time guidance to help users classify waste into organic, recyclable, and e-waste streams[cite: 1].

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
   git clone [https://github.com/anaghamadhu25/SortSmart-Waste-Awareness.git]
   cd SortSmart-Waste-Awareness
2. **Install required dependencies:**
    ```bash
    pip install -r requirements.txt
3. **Run the Streamlit web application:**
    ```bash
    python -m streamlit run app.py
