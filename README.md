# Project Overview
This project entails an exploratory data analysis (EDA) of a music store database. The purpose of this analysis is to uncover insights into the store's operations, sales performance, customer behaviors, and inventory management. By leveraging SQL for data querying and analysis, we aim to provide a comprehensive understanding of the store's data, identify trends, and offer actionable recommendations for business improvement.

# Database and tools
* Postgre SQL
* PgAdmin4
  
schema music-store database
![data_schema](https://github.com/Pramodnaik12/SQL_Music_Store_Exploratory_Data_Analysis_Project/assets/91789384/aa844b03-c6eb-4a03-b177-ccde8746e706)

# Database Description
The music store database is a relational database comprising several interconnected tables that capture various aspects of the store's operations. Key tables in the database include:
* Customers: Contains information about the store's customers, including their names, contact details, and demographic information.
* employee: contains information about the store's employees, including their names,position and contact details.
* Invoices: Records details of each sale, including the date, total amount, location and the customer who made the purchase.
* Invoice_line: Breaks down each invoice into individual items, detailing the specific tracks sold, quantities, and prices.
* Tracks: Lists all tracks available in the store, including track names, album associations, media types and genre classifications.
* Albums: Contains information about albums, including album titles and artist names.
* Artists: Lists all artists whose tracks are available in the store.
* Genres: Categorizes tracks into various musical genres.
* Media_Types: Describes the different formats in which tracks are available.
* Playlists: Provides details of playlists curated by the store, including playlist names and the tracks they contain.

# Analysis Objectives
The EDA aims to achieve the following objectives:
* Sales Analysis: Evaluate sales performance over time, identify top-selling tracks, albums, and genres, and analyze customer purchasing patterns.
* Customer Insights: Understand customer demographics and behaviors, identify high-value customers, and explore customer retention rates.
* Inventory Management: Assess inventory turnover, identify popular and underperforming tracks, and evaluate the effectiveness of the store's inventory strategies.
* Artist and Genre Trends: Analyze trends in music preferences by examining the popularity of different artists and genres over time.


# Questions answered
1. Who is the senior most employee based on job title?
2. Which countries have the most Invoices?
3. What are top 3 values of total invoice?
4. Which city has the best customers? We would like to throw a promotional Music
Festival in the city we made the most money. Write a query that returns one city that
has the highest sum of invoice totals. Return both the city name & sum of all invoice
totals
5. Who is the best customer? The customer who has spent the most money will be
declared the best customer. Write a query that returns the person who has spent the
most money
6. Write query to return the email, first name, last name, & Genre of all Rock Music
listeners. Return your list ordered alphabetically by email starting with A
7. Let's invite the artists who have written the most rock music in our dataset. Write a
query that returns the Artist name and total track count of the top 10 rock bands
8. Return all the track names that have a song length longer than the average song length.
Return the Name and Milliseconds for each track. Order by the song length with the
longest songs listed first
9. Find how much amount spent by each customer on artists? Write a query to return
customer name, artist name and total spent
10. We want to find out the most popular music Genre for each country. We determine the
most popular genre as the genre with the highest amount of purchases. Write a query
that returns each country along with the top Genre. For countries where the maximum
number of purchases is shared return all Genres
11. Write a query that determines the customer that has spent the most on music for each
country. Write a query that returns the country along with the top customer and how
much they spent. For countries where the top amount spent is shared, provide all
customers who spent this amount



 
