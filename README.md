The Social Network (or How Do You Know Kevin?)
================

At any large gathering with my friends, it seems the conversation inevitably turns to how the hell we all came to know each other. Admitedly, I've never been total clear on that point myself. I'll scan the room full of this [ragtag bunch of misfits](https://tvtropes.org/pmwiki/pmwiki.php/Main/RagtagBunchOfMisfits) and always ask myself the same question...

<img src="https://memegenerator.net/img/instances/36549336/who-are-these-people.jpg" alt="no caption" width="200" />

First Contact
-------------

In an effort to settle the question once and for all, I (naturally) created a spreadsheet. [This Google Sheet](https://docs.google.com/spreadsheets/d/1YsUYg0vrxi9oyW-0IcuE8XfAKGZb6MR7VlpmdChGI0A) contains friends' names as well as each person's list of **"First Contacts"**.

By First Contact, I mean who are the people you would have known without an introduction from someone else? For example, my First Contacts include anyone who went to Westtown as well as Sandy. However, I wouldn't have met anyone from Barleysheaf if it wasn't for one of my First Contacts.

| Name    | FirstContact                                     |
|:--------|:-------------------------------------------------|
| Kevin   | Jordan, Glen, Josh, Lindsay, Sean, Adam, Skonier |
| Adam    | Kevin, Lindsay, Skonier                          |
| Nate    | Allie                                            |
| Holland | Skonier, Tad, Megan                              |

I know I've gotten some of these wrong. Please update & add to [the spreadsheet!](https://docs.google.com/spreadsheets/d/1YsUYg0vrxi9oyW-0IcuE8XfAKGZb6MR7VlpmdChGI0A)

Clusters of Contacts
--------------------

It's tempting to put people into categories, like the "Westtown group" or the "Barleysheaf group". However, some people fit into many such groups, and some fit into none at all. Instead of categorizing people manually, we can turn to [cluster analysis](https://en.wikipedia.org/wiki/Cluster_analysis) to automatically categorize individuals based on who their first contacts are. We'll start with four clusters for now, though that may need to be updated as more data is added.

Visualising the Connections
---------------------------

Finally, we can use all this information to create a network plot of all individuals and their connections to each other. Each individual is color-coded based on their cluster. We can see for example that most of the Westtown group forms a distinct cluster, as does the Dickinson group. Significant others are a distinct cluster as well! I'm very curious to see how this evolves as more individuals and connections are added.

    ## Warning in grid.Call(C_textBounds, as.graphicsAnnot(x$label), x$x, x$y, :
    ## font family not found in Windows font database

    ## Warning in grid.Call(C_textBounds, as.graphicsAnnot(x$label), x$x, x$y, :
    ## font family not found in Windows font database

![](README_files/figure-markdown_github/social_network-1.png)

High-quality canvas prints will be available for sale shortly.
