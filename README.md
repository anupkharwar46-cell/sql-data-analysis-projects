# Spotify_SQL_Project-and-Query_Optimization
![Spotify_Logo](https://github.com/user-attachments/assets/75b759c3-a0ac-4030-b0d0-ee8bbe3fe697)

# OVERVIEW
This project involves analyzing a Spotify dataset with various attributes about tracks, albums, and artists using SQL.
 It covers an end-to-end process of normalizing a denormalized dataset, performing SQL queries of varying complexity (easy, medium, and advanced), and optimizing query performance.
 the primary goal of this project is practise on Advanced Sql skills and generate valueable insight from in it.






# -----**Create Table**:-----



![Table](https://github.com/user-attachments/assets/04c07c30-a93b-441e-8a4e-b024fd4ab08f)



  
  
 # ------ **Query:**----- 

  
                                    There Are three Category


**Easy Queries**
Simple data retrieval, filtering, and basic aggregations.


**Medium Queries**
More complex queries involving grouping, aggregation functions, and joins.


**Advanced Queries**
Nested subqueries, window functions, CTEs, and performance optimization.



## **Questions**


**Easy Category**
1. Retrieve the names of all tracks that have more than 1 billion streams.
2. List all albums along with their respective artists.
3. Get the total number of comments for tracks where licensed = TRUE.
4. Find all tracks that belong to the album type single.
5. Count the total number of tracks by each artist

   


**Medium Category**


6. Calculate the average danceability of tracks in each album.
7. Find the top 5 tracks with the highest energy values.
8. List all tracks along with their views and likes where official_video = TRUE.
9. For each album, calculate the total views of all associated tracks.
10. Retrieve the track names that have been streamed on Spotify more than YouTube.



**Advanced Category**

11. Find the top 3 most-viewed tracks for each artist using window functions.
12. Write a query to find tracks where the liveness score is above the average.
13. Use a WITH clause to calculate the difference between the highest and lowest energy values for tracks in each album.--
->



<img width="708" height="220" alt="image" src="https://github.com/user-attachments/assets/5d542995-bfcd-4f36-bf86-e90983c30816" />





14. Find tracks where the energy-to-liveness ratio is greater than 1.2.
15. Calculate the cumulative sum of likes for tracks ordered by the number of views, using window functions.





# **Query Optimization Technique**



### ---Query:- This is The Query , Where we will add Index..

<img width="874" height="65" alt="image" src="https://github.com/user-attachments/assets/5df4c2aa-8cf5-4dfb-bf35-6b9198cfcbbe" />


## ---**Before Index**--


![SQL_Before_Index](https://github.com/user-attachments/assets/b8f001f8-b70c-468b-8ad4-3fdbc8847eda)


## --**Index Creation on the Order view Column**--

creating... Index

![Index](https://github.com/user-attachments/assets/4305f56c-8ff3-407a-a950-2eca91d74741)



## --**After Index**--

After Creating Index...

![SQL_After_Index](https://github.com/user-attachments/assets/1db15187-0a69-4f49-9fa2-ccb0fc32d43b)



## --**Graphical Performance Comparison**---


### Explain...

![Graphical](https://github.com/user-attachments/assets/5d94b474-49c5-4fdc-bd4f-ec4b52861f76)

## And

### Graphical...

![Graphical_](https://github.com/user-attachments/assets/3582ba04-c459-4a39-883d-b34e9c358833)

# Technology Stack

## **1.Database:** PostgreSQL
##  **2.SQL Queries:** DDL, DML, Aggregations, Joins, Subqueries, Window Functions
##  **3.Tools:** pgAdmin 4 (or any SQL editor), PostgreSQL (via Homebrew, Docker, or direct installation)

# How to Run the Project
## 1.Install PostgreSQL and pgAdmin (if not already installed).
## 2.Set up the database schema and tables using the provided normalization structure.
## 3.Insert the sample data into the respective tables.
## 5.Execute SQL queries to solve the listed problems.
## 6.Explore query optimization techniques for large datasets.


# Next Steps
## Visualize the Data: Use a data visualization tool like Tableau or Power BI to create dashboards based on the query results.
## Expand Dataset: Add more rows to the dataset for broader analysis and scalability testing.
## Advanced Querying: Dive deeper into query optimization and explore the performance of SQL queries on larger datasets.













