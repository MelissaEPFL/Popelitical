![image](data/popefrancis2.jpg)

At first glance, one might think that the pope does not have much impact on our everyday life and on our country’s politics, yet his opinion affects over 1.3 billion Catholics worldwide and regularly meets with the most powerful political figures of the planet. Here, we want to investigate how one of the mightiest apolitical figures on Earth influences one sixth of the world population by using a novel quotations corpus : **Quotebank**. 

  
Our main approach consists in placing the pope on the American political spectrum, alongside to a few emblematic Democras and Republicans politicians, by extracting meaningful features from the quote corpus of each of our selected speakers. More precisely, we focused on analysing how important key topics such as politics, economics, war and religion were to our speakers by looking at the prominent lexical fields present in their statements.
 
## Why the American political spectrum?

We chose to place the pope on the **American bipartite political spectrum** which comprises at its two ends the Democratic Party and the Republican Party. This spectrum is particularly suited for our analysis, first, because the Quotebank corpus main language is English which means that a significant portion of the quotes originate from american politicians and secondly because choosing a binary spectrum simplifies our analysis a lot.
  
We divided our speakers into three categories: **Democrats**, **Republicans** and the **pope**. Here we briefly summarize which speakers we chose to integrate into our analysis and how many quotes they pronouced along the Quotebank data sets between 2015 and 2020.


| Political figure | Party      |Number of quotations |  |Political figure | Party      |Number of quotations |  
|------------------|------------|----------------------| |------------------|------------|----------------------| 
| Elizabeth Warren | Democratic | 48'397               | | Ted Cruz         | Republican| 46'301               |
| Bernie Sanders   | Democratic | 84'018               | |Marco Rubio      | Republican| 41'650               |
| Hillary Clinton  | Democratic | 95'458               | | Mike Pence       | Republican| 46'893               | 
|Kamala Harris    | Democratic | 19'091               |  |Ben Carson     | Republican| 22'448                 |
|Pete Buttigieg   | Democratic | 24'523              |   | Mitt Romney      | Republican| 10'651               |
|Alexandria Ocasio-Cortez  | Democratic | 18'653     |   |Nikki Haley     | Republican| 24'533               |   
| Pope Francis        | Apolitical| 102'993          |
  

## What topics do they like to talk about? 
  
We begin our investigation by looking at how our three categories of speakers choose their words and what topics they fancy talking about the most. To do so, we analyzed the prevalence, summarized by a mean score, of 200 distinct lexical fields within the quotation corpus of our three categories:

![image](output/Top_lexical_fields_each_category.jpg)

Those first results make a lot of sense as they show that our two political categories often talk about *government*, *business*, *leader*, *politics* and *law* while the Pope prefers to talk about *religion*, *divine* and *worship*-related topics. As an example, the *worship* lexical field score increases when the Pope uses words such as : "pray", "lord", "bless", "glory" or "cult". At the bottom of the graph, we find the most rarely used lexical fields with notably the *exotic*, *smell* and *ugliness* lexical fields. We can also note that the Pope is a true saint as he never uses swearing words!

## Do they talk about similar topics?

As a next analysis, we wanted to determine how similar or different the usage of lexical fields was across our three groups. One first simple idea consisted in computing the correlation matrix (Pearson's correlation coefficient) of the 200 mean lexical fields scores of our three categories.

<a href="link" style="text-align: center">
<img src="output/Correlation_matrix_each_category.jpg" align = "center" width="60%" height="60%"> </a>

The lexical fields scores of the Republicans and Democrats are very strongly correlated (0.94). This could be due to the fact that even though the two parties have different opinions, they allocate similar importance to the same topics. On the other hand, the pope's lexical fields scores correlate more modestly with those of of the Democrats and Repuclicans. From this measure, he seems to be slightly closer from the Republicans (0.45) than from the Democrats (0.39).  


We then decided to focus on the 15 most prominent lexical fields of our three categories, removed the dupplicates and compared their relative use:

{% include horizontal_bar_plot.html %}

As we can see, the pope seems to leave political topics such as *government*, *business*, *politics*, *leader*, *law*, *money*, *banking*, *dispute* and *payment* to the real politicians. As the head of the Church, he is logically more commonly refering to religion-related topics such as *worship*, *religion*, *love*, *divine*, *death* and *wedding* than the politicians. Interestingly, the lexical fields *family*, *children*, *home*, *positive emotions* and *optimism* are also dominated by the pope. Concerning the *family*, *children* and *home* lexical fields, it might be due to the fact that the pope uses the terms "brother", "sister", "father", "mother" and "son" a lot, even though he barely uses the litteral meaning of those terms. Concerning the *optimism* and *positive emotions* lexical fields, they include terms like "compassion", "forgiveness", "love", "kindness", "hope" and "faith" which can all be seen as Christian values.

Alternatively, we present here the same results as in the previous graph for a hand-picked selection of lexical field using a radio chart in order to emphasize how different the profile of the Pope is in comparison with the profiles of the Democrats and Republicans.

{% include radar_chart_features.html %}

We also wanted to visualize which of the 15 most common lexical fields of our three categories are shared. To do so, we built the following Venn diagram:

![image](output/Venn_most_prominent_lexical_fields_across_categories.jpg)

We immediately notice that the two politcal parties share most of their lexical fields, which are all politics-related, while the pope stands out much more. The only lexical fields that are shared by our politicians and by the pope are: *giving* (which includes words like "give", "need", "offer", "fund", "donate", "sacrifice" and "pay"), *positive emotions* and *negative emotions*. Interestingly, none of those three lexical fields is really related to politics. Then, we can observe that the pope shares the *children* lexical field with the Democrats, which may arise from the Democratic party social and family-oriented values. We can also see that the pope-specific lexical fields all concerns religious topics (*religion*, *worship*, *divine*, *wedding*, *death*) and human-oriented topics (*family*, *home*, *love*, *communication*, *optimism*). Those key topics are coherent with the pope's role as the head of the Catholic Church and considering how the catholic faith rythms the most important life events of its followers: baptism at birth, the marriage sacrament and the last rites on one's deathbed.

## What does the pope say? 

We were also interested by the 

<a href="link" style="text-align: center">
<img src="output/wordcloud_edge.png" align = "center" width="60%" height="60%"> </a>

![image](output/network_sparse.png)




## Can we place the Pope on a political spectrum?
Partie sur la PCA

![image](output/PCA_visualization.png)




Small disclaimer concerning the fact that we use quotes relayed by the media: there is a bias
