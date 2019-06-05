The Social Network
================

At any large gathering with our friends, it seems the conversation inevitably turns to how the hell we all came to know each other. Admitedly, I've never been total clear on that point myself. I'll scan the room full of this [ragtag bunch of misfits](https://tvtropes.org/pmwiki/pmwiki.php/Main/RagtagBunchOfMisfits) and always ask myself the same question...

<img src="https://memegenerator.net/img/instances/36549336/who-are-these-people.jpg" alt="no caption" width="200" />

First Contact
-------------

In an effort to settle the question once and for all, I (naturally) created a spreadsheet. [This Google Sheet](https://docs.google.com/spreadsheets/d/1YsUYg0vrxi9oyW-0IcuE8XfAKGZb6MR7VlpmdChGI0A) contains friends' names as well as each person's list of **"First Contacts"**.

By First Contact, I mean who are the people you would have known without an introduction from someone else? For example, my First Contacts include anyone who went to Westtown as well as Sandy. However, I wouldn't have met anyone from Barleysheaf if it wasn't for one of my First Contacts.

| Name  | FirstContact                                  |
|:------|:----------------------------------------------|
| Sean  | Glen, Kevin, Josh, Lindsay, Jordan, Christine |
| Glen  | Jordan, Kevin, Josh, Lindsay, Sean, Katie     |
| Kim   | Tad                                           |
| Allie | Lindsay, Nate                                 |

I know I've gotten some of these wrong. Please update & add to [the spreadsheet!](https://docs.google.com/spreadsheets/d/1YsUYg0vrxi9oyW-0IcuE8XfAKGZb6MR7VlpmdChGI0A)

Clusters of Contacts
--------------------

It's tempting to put people into categories, like the "Westtown group" or the "Barleysheaf group". However, some people fit into many such groups, and some fit into none at all. Instead of categorizing people manually, we can turn to [cluster analysis](https://en.wikipedia.org/wiki/Cluster_analysis) to automatically categorize individuals based on who their first contacts are. We'll start with four clusters for now, though that may need to be updated as more data is added.

Visualising the Connections
---------------------------

Finally, we can use all this information to create a network plot of all individuals and their connections to each other. Each individual is color-coded based on their cluster. We can see for example that most of the Westtown group forms a distinct cluster, as does the Dickinson group. Significant others are a distinct cluster as well! I'm very curious to see how this evolves as more individuals and connections are added.

<img src="README_files/figure-markdown_github/social_network-1.png" style="display: block; margin: auto;" />

High-quality canvas prints will be available for sale shortly.

Alternatives
------------

Glen & Adam suggested that we more clearly show the type of connection between each person. This gets kind of complicated since we're all "connected" now, but we'll try again to focus on the type of initial connection. This data is stored on a [separate tab of the spreadsheet](https://docs.google.com/spreadsheets/d/1YsUYg0vrxi9oyW-0IcuE8XfAKGZb6MR7VlpmdChGI0A/edit#gid=1618818909) with relationship types like "High School", "Dickinson" and "Married".

I'm also going to break my own rules a bit and show Christine as connected with both Sean and Kevin, mostly because it's weird not to see the Robinsons connected. Aww!!!

<img src="README_files/figure-markdown_github/alternative-1.png" style="display: block; margin: auto;" />
