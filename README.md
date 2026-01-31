# **Netflix content strategy analysis**

## **Project Overview**
This project analyzes Netflix's library (data updated to 2021) using SQL. The goal is to uncover strategic shifts in content production, focusing on geographical dominance, genre trends, and the evolution of movie formats. The dataset was sourced from **Kaggle** and contains information on movies and TV shows available on Netflix up to 2021.

## **Key research objectives**
* Identifying dominant categories in the Netflix library.
* Top 5 producing countries using Window Functions.
* Tracking how movie runtimes have changed over decades.
* Using keyword search to quantify "Action" vs "Love" themes.

## **Tech stack & SQL skills**
* **Tooling:** DataCamp DataLab (SQL / Jupyter Notebook).
* **Skills Demonstrated:**
    * **CTEs** (Common Table Expressions) for logical data layering.
    * **Window Functions** (`RANK() OVER`) for advanced ranking within categories.
    * **Data Aggregation:** using `COUNT`, `SUM`, and `GROUP BY` to summarize data.
    * **Conditional Logic:** using `CASE WHEN` for keyword identification.

## **Key insights**
* Modern movies consistently converge around the 90-100 minute mark.
* While the US leads overall, India dominates in Movie volume, while the UK and Japan show strong TV Show presence.
* Plot descriptions feature "Love" significantly more often than "Action", reflecting a heavy investment in romantic and human-interest narratives.
