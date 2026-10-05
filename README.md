# App Store Market Analytics Dashboard

An interactive Power BI dashboard for analyzing App Store performance, pricing strategies, app size profiles, localization, and user engagement.

**Author:** Tran Hoang Phuc
**Project type:** Capstone Project
**Tool:** Microsoft Power BI
**Data source:** App Store Market Data (apps released between 07/2008 and 10/2019)

---

## Dashboard Preview

| Home | Overview |
|------|----------|
| ![Home](images/home.png) | ![Overview](images/overview.png) |

| Pricing & Tech | Global |
|----------------|--------|
| ![Pricing & Tech](images/pricing-tech.png) | ![Global](images/global.png) |

> Tip: export each page from Power BI Desktop (File > Export > PDF, then convert to PNG) and place the images in an `images/` folder.

---

## Project Overview

This dashboard explores the App Store market from three angles:

1. **Overview**: market size, ratings, user engagement, and genre performance.
2. **Pricing & Tech**: how price and app size relate to ratings.
3. **Global**: language support and localization opportunities.

Global filters (Primary Genre, Price Category, Age Group) and a date range slicer let users drill into any segment.

---

## Dashboard Pages

### 1. Overview
- KPIs: Total Apps (16,847), Avg Rating per App (4.06), User Rating count (24.76M), Total Languages (115), Avg Size per App (115.81 MB), each split by Free vs Paid.
- App Pricing Tiers (Free, under $10, over $10)
- Target Audience & Age Rating (Kids and Family vs Teens and Adults)
- App Storage Profile by size bucket
- Monthly Launch Trend
- Genre Performance Matrix (avg rating, genre share, total apps, total reviews, avg reviews, languages)

### 2. Pricing & Tech
- KPIs: Avg Price Paid ($5.01), % Paid App (16.3%), Total App, Avg App Size, % App Under 500MB (96.8%), with comparison vs YTD last year.
- Scatter plot of app size vs price
- Total apps by price tier
- App Size & Price Performance matrix (avg rating / user rating)
- Decomposition tree: Genre > Price > App Size performance

### 3. Global
- KPIs: Total Languages (115), Avg Language per App (3.1), % App Available in English (99.3%), Top Language excluding English (Chinese), Apps with a Single Language (12,512).
- Top Languages by App Count (with Top N selector)
- App Distribution and Avg Rating by number of languages supported
- Emerging Opportunity Languages (rating vs market average)
- Localization Trend by Release Year

---

## Key Insights

- The market is dominated by **free apps (83.7%)**, while paid apps account for 16.3%.
- **Games** make up about 96% of all apps in the dataset.
- Roughly **96.8%** of apps are under 500 MB; paid apps are larger on average (149.27 MB vs 109.32 MB for free).
- **English** is available in 99.3% of apps; **Chinese** is the most common additional language.
- Most apps (12,512) support only a single language, which leaves room for localization opportunities.

---

## Repository Structure

```
.
├── Capstone_Project_1_Tran_Hoang_Phuc.pbix   # Power BI report
├── Capstone_Project_1_Tran_Hoang_Phuc.pdf    # Exported dashboard (PDF)
├── images/                                   # Dashboard screenshots
└── README.md
```

---

## How to Use

1. Download or clone this repository.
2. Open `Capstone_Project_1_Tran_Hoang_Phuc.pbix` with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
3. Use the page navigation buttons and slicers to explore the data.

---

## Skills Demonstrated

- Data modeling and DAX measures
- Dashboard design and navigation (buttons, slicers, bookmarks)
- KPI cards, decomposition tree, scatter plot, matrix, and trend charts
- Business storytelling with data

---

## Contact

**Tran Hoang Phuc**
GitHub: [PhucTran289](https://github.com/PhucTran289)
