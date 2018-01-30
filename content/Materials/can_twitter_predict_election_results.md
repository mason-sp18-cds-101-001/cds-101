Title: Can Twitter predict election results?
Author: Dr. Glasbrenner
Author_Image: https://www.gravatar.com/avatar/49802fdfa5a0e63b3d932a5179d41c1e
Date: 2018-01-23 13:30
Tags: activity
Slug: class-1-twitter-activity
Summary: An introductory activity about a data science study that used Twitter data to predict election outcomes.
Show_summary: true
Show_link: true

## Appearances of candidates' names on Twitter can help predict election results

The promise of using data science to predict election results has been received a lot of attention over the last decade.
A lot of attention has focused on using polls to create models and predict results, such as what Nate Silver does over at [fivethirtyeight.com][538].
Besides polls, other kinds of data have been focused on for making predictions about elections.
Consider the following 2013 study by a group of researchers at Indiana University.
They wanted to see if the appearances of candidates’ names on Twitter can help predict election results.

The Washington Post picked this up in an editorial, written by one of the study's authors:

> New research in computer science, sociology and political science shows that data extracted from social media platforms yield accurate measurements of public opinion.
> It turns out that what people say on Twitter or Facebook is a very good indicator of how they will vote.
 
> How good?
> [...]
> co-authors Joseph DiGrazia, Karissa McKelvey, Johan Bollen and I show that Twitter discussions are an unusually good pre- dictor of U.S. House elections.
> Using a massive archive of billions of randomly sampled tweets stored at Indiana University, we extracted 542,969 tweets that mention a Democratic or Republican candidate for Congress in 2010.
> For each congressional district, we computed the percentage of tweets that mentioned these candidates.
> We found a strong correlation between a candidate’s tweet share and the final two-party vote share, especially when we account for a district’s economic, racial and gender profile.
> In the 2010 data, our Twitter data predicted the winner in 404 out of 406 competitive races.

## Data science

This is a true data science research project, in that:

*   The data being analyzed was scraped from the Internet, not collected from a controlled, randomized trial.
    Typical statistical assumptions about random sampling, etc. do not apply!

*   The research question is addressed by combining *domain knowledge* (i.e. knowledge of how Congressional races work) with a data source (Twitter) that has no obvious relevance.

*   A *large* amount of data (500 million tweets!) was collected.
    [Note: only 500,000 tweets were analyzed.]
    In this case, the data was big enough that the Center for Complex Networks and Systems Research had to get involved!

*   The project was undertaken by a team of researchers from different fields (i.e. sociology, computing) working in different departments, and bringing different skills to the table.

## Read the article like a scientist

Spend a few minutes reading the [Rojas editorial][wapo-rojas-editorial] and skimming the [actual paper][digrazia-paper].
Be sure to consider Figure 1 and Table 1 carefully, and address the following questions.

1.  Write a sentence summarizing the findings of the paper.

2.  Discuss Figure 1 with the people near you. What is its purpose? What does it convey?
    Think critically about this data visualization.
    What would you do differently?

3.  Discuss with in your team the differences between the Bivariate model and the Full Model.
    Which one do you think does a better job of predicting the outcome of an election?
    Which one do you think best addresses the influence of tweets on an election?

4.  Why do you suppose that the coefficient of RepublicanTweetShare is so much larger in the Bivariate model?
    How does this reflect on the influence of tweets in an election?

5.  Do you think the study holds water?
    Why or why not?
    What are the shortcomings of this study?

## Study replication

Imagine that you work for a team whose boss, who does not have advanced technical skills or knowledge, asked you to reproduce the study you just read.
Discuss the following in your neighbors.

1.  What steps are necessary to reproduce this study?
    Be as specific as you can!
    Try to list the subtasks that you would have to perform.

2. What computational tools would you use for each task?

## Credits

This classroom activity is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).
Adapted by James Glasbrenner for CDS-101 from [the following activity][duke-sta112-adapted] by [Mine Çetinkaya-Rundel](https://stat.duke.edu/~mc301).
Credit for the dataset example belongs to [Ben Baumer](http://www.math.smith.edu/~bbaumer/).

[538]:                   http://fivethirtyeight.com
[digrazia-paper]:        /doc/DiGrazia2013_SSRN_MoreTweetsMoreVotes-id2235423.pdf
[duke-sta112-adapted]:   https://github.com/mine-cetinkaya-rundel/sta112_f15/blob/8e70667fc8db04f3a65b1c01a57ff747a6c9ed0a/application-exercises/app_Twitter_election_results.Rmd
[wapo-rojas-editorial]:  http://www.washingtonpost.com/opinions/how-twitter-can-predict-an-election/2013/08/11/35ef885a-0108-11e3-96a8-d3b921c0924a_story.html 

