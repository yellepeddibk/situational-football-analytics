# Situational Football Analytics

A data-driven analysis of Iowa State football play effectiveness across situational contexts, developed as part of an ISU Workshop project.

## Project Overview

This project analyzes what plays work best for the **Iowa State Cyclones** football team based on down, distance, and field position using play-by-play data from the 2025 season.

## Analyses

### Down & Distance Effectiveness

Examines average yards gained per play at 3-yard intervals, broken down by down (1st, 2nd, 3rd). Key features:
- **X-axis**: Distance to go (grouped in 3-yard intervals)
- **Color/Legend**: Down number (1st, 2nd, 3rd)
- Provides a clear visual of which down-and-distance combinations were most effective for Iowa State across each game

### Red Zone Success Rate

Examines Iowa State's effectiveness with run vs. pass plays inside the red zone across all 2025 season games. Key features:
- **Red dot**: Average yards gained by a rushing play in the red zone
- **Blue dot**: Average yards gained by a passing play in the red zone
- Broken down by opponent to identify Iowa State's recipe for red zone success against different defenses

## Project Structure

```
situational-football-analytics/
├── .github/
│   └── PULL_REQUEST_TEMPLATE.md  # PR description template
├── data/
│   ├── raw/                       # Raw, unmodified game data
│   └── processed/                 # Cleaned/transformed data
├── notebooks/                     # Jupyter notebooks for analysis
├── outputs/                       # Generated graphs and visualizations
├── reports/                       # Written reports and presentations
├── CONTRIBUTING.md
├── LICENSE
└── README.md
```

## Data

Play-by-play data from Iowa State's 2025 football season, filtered to Iowa State offensive plays only.

**Games analyzed:**
- vs. South Dakota
- vs. Kansas State
- vs. Iowa
- vs. Arkansas State
- vs. Arizona
- vs. Cincinnati

## Contributors

- **Bhargav Yellepeddi** – Project Manager
- **Malachi Taylor** - Project Lead
- **Jacob Gunderson** – Run vs. Pass avg. within Red Zone
- **Andy Kruger** - Yards-per-Play by Quarter
- **Luke Randolph** - Yards-per-Play by Quarter
- **Sawyer Chopskie** - Red Zone Efficiency
- **Julian Mathew** - Offensive Gains Analysis

## License

MIT License — Copyright (c) 2026 Bhargav Yellepeddi, Malachi Taylor, Jacob Gunderson, Andy Kruger, Luke Randolph, Sawyer Chopskie, Julian Mathew