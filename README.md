# Netflix movies and shows (2010–2021)

This is an analysis of the movies and shows of Netflix from the period 2010–2021. It covers the distribution of genres, directors and actors, showing how the genres of the titles vary over time and country, and who are the most popular directors and actors overall and for each type of genre.

---

## Table of contents

- [Movies]
  - Movie releases per year
  - Movie releases per year and genre
  - Distribution of movie genres by country
  - Top movie directors
  - Top movie actors
- [Shows]
  - Show releases per year
  - Show releases per year and genre
  - Distribution of show genres by country
  - Top show directors
  - Top show actors

---

> **Note**  
> When displaying the top directors and actors, I don't show always the same number. I tried to display the top 10 when possible, but sometimes there are a lot of actors or directors with the same number of titles associated to them, making it impossible to fit everything in a top 10 graph. Leaving ones and cutting others from the plot would have been arbitrary; hence, instead of showing a top 10 in those cases, I opted for drawing the line just below the last top actor or director with a distinct number of titles, leaving out the rest who have the same number of productions to their names. This resulted in plots with different top numbers: in some cases I show a top 5, a top 6, etc.

---

## Movies

### Movie releases per year

We start by checking how many movies were released each year. We can see that the number increases each year, with the bigger shift happening between 2015 and 2016. After 2018, the number starts to drop, with the biggest decrease between 2020 and 2021. Personally, I would have expected the number of movies to increase during the pandemic, since one could argue that it would have been in Netflix's best interest to take advantage of the fact that people couldn't go to the theaters; nonetheless, it was also much more difficult to produce the movies because of all the protocols that had to be implemented to minimize contagions, so that gives this result more sense.

![Number of movies released per year](figures/movies_per_year.png)

---

### Movie releases per year and genre

Now that we saw the evolution of movie releases overall, let's see the releases segmented by genre. As the graphic shows, drama and comedy are the genres with the most increase throughout the years, meaning they are the most demanded types of genres. Again, it's visible the huge drop in releases after 2019.  
I decided to group action and adventure into a single category, since every action movie is also labeled as adventure in the dataset, which would cause them to overlap if we try to plot them separately.

![Number of movie releases per year, by genre](figures/movie_releases_by_year_and_genre.png)

---

### Distribution of movie genres by country

Let's check the popularity of each genre by country. Of course, I didn't consider all the countries in the dataset, since that would have been chaotic. I took a sample of 11 countries to show. It's evident that drama and comedy are the most popular types of movies in most countries, with exceptions like Japan in which action/adventure beat both genres, and South Korea, where action/adventure is at a similar level than comedy but still less than drama.

![Distribution of movie genres by country](figures/movie_genres_by_country.png)

---

## Top movie directors

Now we will begin to explore the top movie directors, considering directors across all genres first, and then separating by genre.

![Top movie directors](figures/top_movie_directors.png)

### Top comedy movie directors

![Top comedy movie directors](figures/top_comedy_movie_directors.png)

### Top action/adventure movie directors

![Top action/adventure movie directors](figures/top_action_adventure_movie_directors.png)

### Top drama movie directors

![Top drama movie directors](figures/top_drama_movie_directors.png)

### Top horror movie directors

![Top horror movie directors](figures/top_horror_movie_directors.png)

### Top sci-fi movie directors

![Top scifi movie directors](figures/top_scifi_movie_directors.png)

### Top documentary movie directors

![Top documentary movie directors](figures/top_documentary_movie_directors.png)

---

## Top movie actors

As for the directors, we will start with the top movie actors overall and then separating by genre.

![Top movie actors](figures/top_movie_actors.png)

### Top comedy movie actors

![Top comedy movie actors](figures/top_comedy_movie_actors.png)

### Top action/adventure movie actors

![Top action/adventure movie actors](figures/top_action_adventure_movie_actors.png)

### Top drama movie actors

![Top drama movie actors](figures/top_drama_movie_actors.png)

### Top horror movie actors

![Top horror movie actors](figures/top_horror_movie_actors.png)

### Top documentary movie actors

![Top documentary movie actors](figures/top_documentary_movie_actors.png)

I find it funny to see Neil deGrasse Tyson categorized as an actor here, but since he is the presenter of many documentaries, he is part of the cast, which technically makes him an actor.

### Top sci-fi movie actors

![Top scifi movie actors](figures/top_scifi_movie_actors.png)

---

## Shows

We will do the same analysis for the shows as we did for the movies.

### Show releases per year

Here we see the same pattern as we did for the movies, with an increasing trend up until 2020 and then a significant decrease thereafter. It's worth noting that the number of shows released continued to rise past 2018, whereas in the case of the movies the drop started in 2019.

![Number of shows released per year](figures/shows_per_year.png)

---

### Show releases per year and genre

![Number of show released per year, by genre](figures/show_releases_by_year_and_genre.png)

---

### Distribution of show genres by country

![Distribution of show genres by country](figures/show_genres_by_country.png)

---

## Top show directors

![Top show directors](figures/top_show_directors.png)

Since the directors with the most number of shows directed only appear in two shows, it doesn't make sense to do a particular analysis of the top directors for each genre, because most of them will only have one show to their names.

---

## Top show actors

![Top show actors](figures/top_show_actors.png)

### Top comedy show actors

![Top comedy show actors](figures/top_comedy_show_actors.png)

### Top action/adventure show actors

![Top action/adventure show actors](figures/top_action_adventure_show_actors.png)

### Top drama show actors

![Top drama show actors](figures/top_drama_show_actors.png)

### Top horror show actors

![Top horror show actors](figures/top_horror_show_actors.png)

### Top documentary show actors

![Top documentary show actors](figures/top_documentary_show_actors.png)

### Top sci-fi show actors

![Top scifi show actors](figures/top_scifi_show_actors.png)
