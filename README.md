# Madhav Ecommerce Sales Dashboard
PowerBI Project Analyzes

## The Situation:
Help Madhav Store owner create a dashboard to track and analyze their online sales across India

## The Brief:
The Owner needs a way to track KPIs, compare Location, amount, quantity of product sales.

## The Objective:

#### 1. Connect and Transform the Raw Data
Using Query Editing Tools in **PowerBI** Transform the raw data in the back-end, and organized them before loading data into front-end of PowerBI

#### 2. Build a Relational Data Model
There are two dataset: 
1. [Details.csv](https://github.com/SudesnaDebnath/Madhav-Store/blob/main/Data%20Set/Details.csv)
2. [Orders.csv](https://github.com/SudesnaDebnath/Madhav-Store/blob/main/Data%20Set/Orders.csv)

Use one-to-many mapping between Orders Table & Details Table

**Note:**
1. Fact Table -> Orders Table
2. Dimension Table -> Details Table
3. Primary Key(PK) -> Orders Table[Order Id]
4. Forign Key(FK) -> Details Table[Order Id]

**Rules:**
1. Building a normalized model.
2. Oraganized dimension(lookup) tables above fact(data) tables
3. Avoid complex relationships unless absolutely necessary
4. Hide fields from report view to prevent invalid filter context

#### 3. Design an Interactive Dashboard to Visualize the Data

Use Matrix, Slicers, Bar Charts, Donut Chart, Treemap,Cards, ...etc.

Filtering, formating, and design to get better view for end-user.

Use Bookmarks capture the current state of a page, and allow users to return to that state using report actions.

And also create Mobile Layout.

**Target:** Easy to understand for end-user

## Conclusion: 
A well-designed dashboard should serve a distinct purpose for a distinct audience, use clear and effective metrics and visuals, and provide a simple, intutive user experience.

[Check Dashboard](https://github.com/SudesnaDebnath/Madhav-Store/blob/main/Madhav%20Store%20Report.pbix)
