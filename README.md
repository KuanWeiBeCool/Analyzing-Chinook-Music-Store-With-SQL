# Chinook-Music-Store-Data-Analysis-Using-SQL
Chinook database is a media-related database that contains data about Chinook Music Store. The database contains 11 different tables: album, artist, customer, employee, genre, invoice, invoice_line, media_type, playlist, playlist_track, and track. In this project I will apply my SQL skills to answer the following questions:

- What are the most popular and the least popular genres?
- What are the most popular genres in each country?
- Who is the best sales support agents?
- What are the portions of whole album purchase and individual track purchase?

## Code and Resources Used
**Python Version**: 3.7

**SQL**: SQLite

**Data Source**: https://www.kaggle.com/samaxtech/chinook-music-store-data

## Key Findings
- What are the most popular and the least popular genres?

Based on the result above, Rock, Metal and Alternative & Puck music are the best options to boost the sales volume. The other great choices are Latin, R&B/Soul, Blues, Jazz, and Alternative music. The store should avoid purchasing more tracks in Heavy Metal, Soundtrack, TV Shows, Drama, Bossa Nova, Opera, Rock And Roll, Sci Fi & Fantasy, Science Fiction, and World, as they have very low sales.

- What are the most popular genres in each country?

The favorite genre for almost all countries is Rock. Only Argentina people like Alternative & Punk the most. Therefore, the sales support agents may recommend Rock music for most of the new customers, if they do not have any specific music to purchase in mind.

- Who is the best sales support agents?

There are three support agents in the shop. The best-performed sales support agent is Jane Peacock. Margaret Park has slightly less performance, and Steve Johnson has the least performance. Interestingly, the average dollars spent by each customer are the same for Steve Johnson and Margaret Park. However, Margaret Park has a much higher number of customers than Steve Johnson. This indicates that Margaret Park is better at supporting new customers. Jane Peacock has a similar number of customers with Margaret Park, but her customers spend more money on average in-store. It implies that Jane Peacock has a stronger skill at persuading customers to purchase more products.

- What are the portions of whole album purchase and individual track purchase?

Study the portions of whole album purchase versus individual track purchase can be useful to help the store making management decisions. For example, if the whole album purchase is small, it will be better for the store to purchase the most popular tracks from each album from record companies, instead of purchasing every track from an album. Therefore, my task here is to analyze whether it is a reasonable decision to purchase the most popular tracks. It was found that 18% of the purchase comes from whole album purchase. Consider its large portion on the purchase, it is not recommended to remove the whole albums in the shop. 

**Please check *Analyzing Chinook Music Store With SQL.ipynb* for the complete project.**
