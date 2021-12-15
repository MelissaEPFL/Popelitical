![image](data/popefrancis2.jpg)

<div style="text-align: justify"> 

At first glance, one might think that the Pope does not have much impact on our everyday life and on our country’s politics, yet his opinion affects over 1.3 billion Catholics worldwide and regularly meets with the most powerful political figures of the planet. Here, we want to investigate how one of the mightiest apolitical figures on Earth influences one sixth of the world population by using a novel quotations corpus : <b>Quotebank<\b>. 

  
Our main approach consists in placing the Pope on the American political spectrum, alongside to a few emblematic Democrates and Republicans politicians, by extracting meaningful features from the quote corpus of each of our selected speakers. More precisely, we focused on analysing how important key topics such as politics, economics, war and religion were to our speakers by looking at the prominent lexical fields present in their statements.

</div>
  
## Why the American political spectrum?

<div style="text-align: justify"> 

We chose to place the Pope on the <b>American bipartite political spectrum<\b> which comprises at its two ends the Democratic Party and the Republican Party. This spectrum is particularly suited for our analysis, first, because the Quotebank corpus main language is English which means that a significant portion of the quotes originate from american politicians and secondly because choosing a binary spectrum simplifies our analysis a lot.
  
We divide our speakers into three categories: <b>Democrates<\b>, <b>Republicans<\b> and the <b>Pope<\b>. Here we briefly summarize which speakers we chose to integrate into our analysis and how many quotes they pronouced along the Quotebank data sets between 2015 and 2020.

</div>  
  
| Political figure | Party      |Number of quotations |     | Political figure | Party      |Number of quotations |  
|------------------|------------|----------------------|    |------------------|------------|----------------------| 
| Elizabeth Warren | Democratic | 48'397               |    | Ted Cruz         | Republican| 46'301               |  
| Bernie Sanders   | Democratic | 84'018               |    | Mike Pence       | Republican| 46'893               |
| Hillary Clinton  | Democratic | 95'458               |    | Mitt Romney      | Republican| 10'651               |
| Kamala Harris    | Democratic | 19'091               |    | Marco Rubio      | Republican| 41'650               |
| Pete Buttigieg   | Democratic | 24'523              |     | Ben Carson     | Republican| 22'448                 |
| Alexandria Ocasio-Cortez  | Democratic | 18'653     |     | Nikki Haley     | Republican| 24'533               |
| Pope Francis        | Apolitical| 102'993            |

## What topics do they like to talk about? 
First, to investigate the Pope's position on the American political spectrum, it would be very meaningful to extract and analyse the most discussed topics by each party and by the Pope. A relevant way to do this is to study the most used lexical fields in the quotes of each speaker.  

### What lexical fields are used?
Let's first take a look at all the the lexical field categories that are used by each group.

![image](output/Top_lexical_fields_each_category.jpg)

We observe that the results are coherent for both political parties (with most frequent lexical fields such as governement, business, leader, politics, economics, law) but also for a religious figure such as the Pope (with divine, worship and religion).

### Do the lexical fields of the Pope correlate with those of the two parties?
Then, we further investigate the correlation in the use of lexical fields between each group.

<img src="output/Correlation_matrix_each_category.jpg" width="60%" height="60%">

The lexical fields between Republicans and Democrats are highly correlated (0.94). This seems consistent because even though the two parties approach issues differently and have different opinions, they both most likely use very political language. In contrast, the Pope's lexical fields correlate poorly with those of both political parties, but slightly more with those of the Republicans (0.45) than those of the Democrats (0.39).  

{% include radar_chart_features.html %}


### What are the most shared topics between the groups?
We select the 15 most common lexical fields for all three categories and observe theirs relative use and importance
{% include horizontal_bar_plot.html %}

![image](output/Venn_most_prominent_lexical_fields_across_categories.jpg)


<img src="output/wordcloud_edge.png" width="30%" height="30%">
## Can we place the Pope on a political spectrum?
Partie sur la PCA
