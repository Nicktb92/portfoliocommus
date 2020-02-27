#### Student: Nick ten Broeke
#### Stud. number: 11912219

### Choice of Corpus

The corpus that I have chosen is one of my personally curated playlists, consisting of 406 songs. This particular playlist, called “SN”, is similarly compiled as many of Spotify’s curated playlisted in the sense that it’s not compiled based on genre but rather on a specific mood. Its intention is to be listened to when hanging out, or having dinner with friends. Specifically, I would like to know how the style of this particular playlist has evolved over the years. Did I have different ideas on what fitted the playlist two years ago as opposed to now?

***

### Mean Change

Before I'll look at any visualizations it is important to determine which features changed significantly over the years. Below is a simple line graph that compares two points in time: SN old, comprising of the first 100 added songs in the playlist and SN new, comprising of the latest 100 additions. Red lines in the plot indicate strong effects whereas orange lines describe medium effects.

***

![](MeanChange.png)

The graph suggests that over time the playlist has become more upbeat as the danceability and valence features have increased over time when comparing SN old with SN new. Only comparing the means however gives little inside how the distribution of these features have developed. 

***

### Changes over Time

On the left is a plot that shows how the distribution of the danceability and valence features has shifted over time. The first panel represents SN old (first 100 songs) and the last panel SN old (last 100 songs). To further show how the density of songs on these two dimensions has moved over time, I added a mid panel which I called SN mid, representing a 100 songs that were added in between SN old and new.

The strongest shift can be seen in the valence feature: whereas the majority of songs added in the beginning of the playlist are categorized as sad, with valences centering between 0.1-0.4, the latest songs added show virtually no focus at this region and include songs that explore the upper end of the continuum. Danceability too, has made a shift, albeit less strong than the valence feature. 

What might have caused this shift in sound?

***

![](Density.png)

***

### Constancy

One possibility as a cause for the above shift in distribution is the influence of newly released music. Possibly the shift in playlist sound has less to do with a change in me and my girlfriend but rather has something to do with what is the latest and greatest music that's being released at any given time. The plot below shows that this is probably not the case. The date that songs were added are plotted against the time that they were released to see if there is a relationship between these two variables. To further underline this, I plotted a regression line which turned out almost completely flat. The plot further shows the distribution of the popularity of the tracks added over time, there seems to be a little bit of an overrepresentation of popular songs towards the latest additions but overall there seems to be a roughly equal distribution of popular/unpopular songs at any point in time.

***

![](Constant.png)

