# What is America's favourite Star Wars movie?

Using responses to a Star Wars survey by [FiveThirtyEight](https://github.com/fivethirtyeight/data/tree/master/star-wars-survey) this project uses descriptive statistics and data visualisation to answer the following key questions:

1. What is the highest ranked movie?
2. What is the most viewed movie?
3. Who are the most and least popular characters?
4. Which character is the most controversial?
5. Do the movie rankings and viewing popularity differ by gender?
6. Are the demographics of fans different from non-fans?

## The main findings are:

1. Star Wars Episode V: The Empire Strikes Back is the highest ranked movie.
2. Unsurprisingly the most viewed movie was also Star Wars Episode V: The Empire Strikes Back.
3. The most popular character was Han Solo whilst the least popular was Jar Jar Binks.
4. Jar Jar Binks and Emporer Palpatine are the most controversial characters with similar numbers of favourable and unfavourable ratings from respondents.
5. Star Wars episode V is the most popular movie for both genders and is also the movie which has been seen the most. However there are some differences with females, on average, ranking episode 1 more highly than episode 4, whilst the opposite is true for males. More males than females have seen the latest movies (epsidoes 1-3) and yet males rank these films worse, on average, than females.
6. Self-identified Star Wars fans are more likely, than non-fans, to be younger, male, educated to a higher degree level, and from households with higher incomes.

The full analysis can be found in the [star_wars notebook](https://nbviewer.jupyter.org/github/vivek-kotecha/star-wars/blob/main/star_wars_survey.ipynb).

## Selected output

1. What is the highest ranked movie?

![Highest ranked movie](/output/highest_ranked_movie.png)

3. Who are the most and least popular characters?

![Characters popularity](/output/characters_popularity.png)

4. Which character is the most controversial?

![Controversial characters](/output/most_controversial_character.png)

6. Are the demographics of fans different from non-fans?

By Age:

![Age](/output/split_age.png)

By Gender:

![Gender](/output/split_gender.png)

## Installation

First clone the repository in a local folder

git clone https://github.com/vivek-kotecha/star-wars.git

then run the scripts from the terminal with

```
python {filename}.py
```
or
```
python3 {filename}.py
```

## Dependencies

A comprehensive list of current dependencies include the following libraries
```
Pandas (data manipulation)
Numpy (scientific computing)
Matplotlib (plotting)
Seaborn (plotting)
```

