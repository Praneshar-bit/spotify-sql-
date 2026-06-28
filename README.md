## Spotify Advanced SQL Project and Query Optimization P-6

### Project Overview
This project involves analyzing a Spotify dataset with various attributes about tracks, albums, and artists using SQL. It covers an end-to-end process of normalizing a denormalized dataset, performing SQL queries of varying complexity (easy, medium, and advanced), and optimizing query performance. The primary goals of the project are to practice advanced SQL skills and generate valuable insights from the dataset.

```sql
public.spotiCREATE TABLE spoti(
	Artist	VARCHAR(255),
	Track	VARCHAR(255),
	Album	VARCHAR(255),
	Album_type	VARCHAR(100),
	Danceability	FLOAT,
	Energy	FLOAT,
	Loudness	FLOAT,
	Speechiness	FLOAT,
	Acousticness	FLOAT,
	Instrumentalness	FLOAT,
	Liveness	FLOAT,
	Valence	FLOAT,
	Tempo	FLOAT,
	Duration_min	FLOAT,
	Title	VARCHAR(320),
	Channel	VARCHAR(70),
	Views	VARCHAR(15),
	Likes	BIGINT,
	Comments	BIGINT,
	Licensed	BOOLEAN,
	official_video	VARCHAR(10),
	Stream	BIGINT,
	EnergyLiveness	FLOAT,
	most_playedon VARCHAR(20)
);
```
