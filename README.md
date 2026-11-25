# Data Analytics Project — Superstore Sales

**Course:** DAB111 – Introduction to Python Programming (Fall 2026)  
**Student:** Rushabh Mahesh Sanghvi (0899550)

## Project Structure
```text
Data-Analytics-Project/
├── data_preprocessing/
│   ├── original_dataset.csv
│   ├── cleaned_dataset.csv
│   ├── data_exploration_week_1.ipynb
│   └── data_cleaning_week_2.ipynb
├── database/
│   └── project.db
├── README.md
└── requirements.txt
```

## Weekly Progress
- **Week 1:** Exploratory Data Analysis on `original_dataset.csv` (`data_exploration_week_1.ipynb`).
- **Week 2:** Selected 5 columns (`row_id`, `category`, `region`, `sales`, `profit`), removed non-order footer rows and duplicates, exported `cleaned_dataset.csv` (9,994 records), and loaded it into `database/project.db` (`superstore_sales` table).
- **Week 3:** Flask web application development (upcoming).

## Setup & Execution
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run `data_preprocessing/data_cleaning_week_2.ipynb` from the `data_preprocessing/` directory to regenerate `cleaned_dataset.csv` and `database/project.db`.
