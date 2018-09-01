# Animie Japan

## Introduction
I love watching movies, and I know that people have different tastes in movies because of their differences on culture backgrounds, characteristics and value systems. But how about on an aggregated level such as country? What are the most appreciated movies by people in different countries? Are there any differences? 

Movie Box Mojo is a website that provides up-to-date movie box office data around the world. It also has movie ranking list on domestic box office of most of major movie markets. By scraping movie data from this website and merging to the movie ranking list, we can have most of the movie summary data to do the analysis, such as genre, gross and budget.But for some foreign movies, the movie summary data are not available or complete in Movie Box Mojo's data.So I completed the missing data by integrating IMDB's movie summary, including missing genre information of some foreign movies and all the movie plots summary. The data used in this project can be found under 'Data' of this page, while the codes for scraping movie box mojo's movie info can be found under 'Codes'.

The study focus on movie markets of US/Canada, China and Japan, because the distribution of global movie box office is highly concentracting on these 3 markets which contributed more than 50% to global movie revenue. 

![alt text](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Visualization/DonutPlot_2017_Global_Movie_Market_Share_Top3.png)

Among the top3 markets, Japan is quite outstanding in their preferences on animation movies. 40% of their top 20 movies are animation movies. 

![alt text](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Visualization/Bar_2017_Proportion_of_Animation_Movie_in_Top20_Movies_Japan.png)


Their tastes in movie plots are also very different from the other two markets. The key words of plots summeries of the top 20 movies seem to be soft and feminine.

![alt text](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Visualization/WordCloud_Plots_Japan.png)

## Future Research Direction
Analysis on box office panal data to see if there're any changine trends in movie preferences. 

## Index of Repository

|Codes|
|---|
[Scraping](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/BoxMojo_Data_scraping.ipynb)<br> *Codes of scraping movie data from Movie Box Mojo*
[Analysis](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/BoxMojo_Data_scraping.ipynb)<br> *Codes of the analysis, including donut chart of glolbal movie market share 2017, stacked bar chart and grouped bar chart of contributions to total gross by movie elements, horizontal bar chart of key elements ratio to top20, and word clouds of top20 movies' plots summary.*


|Data|
|---|
[|2017 global movie box office](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Data/World_movie_market_2017.xlsx)<br>*2017 global box office data from 2017 Theme Report by MPAA*|
|[Movie Box Mojo data of movies](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Data/movie_data.csv)<br>*Sraped data from Movie Box Mojo*|
|[2017 Top20 movies in US/Canada, China and Japan](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Data/movie_top3_top20.xlsx)<br>*Data used in analysis of top20 movies in top3 movie markets, including domestic gross, genre, plots summary and others.*|
|[2017 movie rank in  US/Canada, China and Japan](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Data/movie_top20_rank.xlsx)<br>*2017 movie ranking from Movie Box Mojo based on domestic gross.*|

|Visualization|
|---|
|[Donut chart of 2017 global box office focus on top3](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Visualization/DonutPlot_2017_Global_Movie_Market_Share_Top3.png)<br>*Distribution of box office around the world 2017 focus on top3 market shares.*|
|[Donut chart of 2017 global box office with all countries' shares](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Visualization/DonutPlot_2017_Global_Movie_Market_Share_Full.png)<br>*Distribution of box office around the world 2017*|
|[Stacked horizontal bar chart of contributions to total box office by movie genres focus on key genres](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Visualization/StackedBar_Contributions_of_Key_Genres_to_Total_Box_Office.png)<br>*Contributions to total box office by genres of top3 movie markets focus on key genres. |
|[Stacked horizontal bar chart of contributions to total box office by movie genres with full labels](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Visualization/StackedBar_Contributions_of_Genres_to_Total_Box_Office_Full.png)<br>*Contributions to total box office by genres of top3 movie markets*|
|[Grouped horizontal bar chart of contributions to total box office by top3 genres](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Visualization/GroupedBar_Contributions_of_Key_Genres_to_Total_Box_Office.png)<br>*Contributions to total box office by top3 genres in Japan among top3 markets.*|
|[Word cloud of plots summaries of 2017 Japan's top20 movies](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Visualization/WordCloud_Plots_Japan.png)<br>*Word cloud of plots summaries of 2017 Japan's top20 movies focus on 6 key words.*|
|[Word cloud of plots summaries of 2017 US/Canada's top20 movies](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Visualization/WordCloud_Plots_US:Canada.png)<br>*Word cloud of plots summaries of 2017 US/Canada's top20 movies focus on 6 key words.*|
|[Word cloud of plots summaries of 2017 China's top20 movies](https://github.com/wyr211/2017-Top3-Movie-Market-Comparison/blob/master/Visualization/WordCloud_Plots_China.png)<br>*Word cloud of plots summaries of 2017 China's top20 movies focus on 6 key words.*|


## Inspiration
[2017 Theme Report](https://www.mpaa.org/wp-content/uploads/2018/04/MPAA-THEME-Report-2017_Final.pdf)

[Taking anime too seriously](https://www.japantimes.co.jp/culture/2013/06/02/books/book-reviews/taking-anime-too-seriously/#.W4mgx5NKgWo)

[Japanese Anime Culture](https://tokyotreat.com/news/japanese-anime-culture)
