# Hotels in Vienna – Data Science 1 Final Project
Date: 08.10.2025

This is a README file describing the Hotels in Vienna Project. The project analyzes hotel data from Vienna to explore simple relationships between **hotel price**, **star rating**, and **distance from the city center**. It was created as part of the *Data Science 1* course to demonstrate **basic data analysis** and **Git skills** and show minimal, reproducible workflow. 

## Data

The dataset used in this project is the **hotels-vienna** dataset, which contains information on **prices and features of hotels in Vienna, Austria**, for a **single weekday night in November 2017**.  

The dataset contains approximately **428 observations**.

---

### Key Variables

| Variable | Description | Type |
|-----------|--------------|------|
| `hotel_id` | Hotel ID | numeric |
| `price` | Price in EUR | numeric |
| `starrating` | Number of stars | numeric |
| `rating` | Average user rating | numeric |
| `center1distance` | Distance from city center (km) | numeric |
| `accommodation_type` | Type of accommodation | categorical |
| `offer` | Indicator if there was an offer | binary |
| `scarce_room` | Indicator if the room was scarce | binary |

---

### Data Source

The data was **scraped from a hotel price-comparison website**, then **anonymized and slightly altered** to preserve confidentiality.  
It was compiled and made available by **Gábor Békés** and **Gábor Kézdi** as part of their open educational resources for the book:

> *Békés, G., & Kézdi, G. (2021). Data Analysis for Business, Economics, and Policy.*  
> Cambridge University Press.

Dataset access and documentation are available at:  
  [https://gabors-data-analysis.com/datasets/#hotels-vienna](https://gabors-data-analysis.com/datasets/#hotels-vienna)


## Folder Structure
hotels-vienna/
│
├── analysis/                
│   └── analysis.ipynb
│
├── data/                    
│   └── hotelbookingdata-vienna.csv # Raw dataset
│
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt


## How to Reproduce
1. Clone the repository  
   `git clone https://github.com/abdullahabrh/hotels-vienna.git`
2. Install dependencies  
   `pip install -r requirements.txt`
3. Open the Jupyter Notebook in `analysis/`

## Author
  - **Abdullah Abdulrahim** - https://github.com/abdullahabrh
