# Use Spotify API to get personal X top tracks and visualize them



NOTE spotify also provides big datasets for research https://research.atspotify.com/datasets/


NEXT TODO add also extracted artists

also very nice, ML with track features https://github.com/jmcabreira-zz/Data-Science-Projects/blob/master/A-Music-Taste-Analysis-Using-Spotify-API-and-Python./Playlist_analysis_%20.ipynb

TODO get all song attributes like here https://medium.com/@eelopez088/data-analysis-with-spotify-api-a1507f48e9b0
        plot correlations, do a pcr to find user patterns, etc 

TODO implement real login https://developer.spotify.com/documentation/web-api/concepts/authorization

Visualize song ranking data
https://www.google.com/search?client=ubuntu-sn&channel=fs&q=ranking+data+visualization
https://libguides.uvic.ca/pick-a-viz/ranking
https://www.quanthub.com/data-storytelling-charts-for-displaying-ranks/

we know the ranking of the tracks based on ur usage (sort and long term)
and we know track, artist, album, etc and popularity (0-100) of all those things
        myb convert gloabl-popularity to gloabl-popularity-rank to compare to my-ranks
so i can compare popularity with my personal ranking in multiple dimensions (track, artist, album, etc.)

NOTE i can also play with the time_range API parameter 'long_term', 'mid_term', 'short_term'
NOTE i can also use an offset as start index in API call to get from 50-100, etc.
        like described here https://github.com/spotify/web-api/issues/1121

here also some nice stuff https://www.tableau.com/data-music
    eg https://public.tableau.com/app/profile/david.pires/viz/Spotify2/TracksAnalysis
    https://public.tableau.com/app/profile/robert.janezic/viz/ALTNATION/AltNation
    https://public.tableau.com/app/profile/pradeepkumar.g/viz/WhatsyourfavouriteMusicGenre/iron_viz_2019


google search https://www.google.com/search?client=ubuntu-sn&channel=fs&q=spotify+api+for+data+science
https://towardsdatascience.com/spotify-api-audio-features-5d8bcbd780b2
https://levelup.gitconnected.com/music-analysis-with-spotify-api-59c080734c6e
https://github.com/jkvaternik/oye
https://observablehq.com/@sandraviz/spotify-artists-d3--step2
https://towardsdatascience.com/step-by-step-to-visualize-music-genres-with-spotify-api-ce6c273fb827
https://github.com/iqbalbasyar/Spotify-for-Data-Science




Visulaisation suggetsions by Claude:

Here's what each visualization reveals:

Artist Distribution Treemap

Shows how many tracks each artist has in your top list
Quickly identifies your most-played artists
Rectangle size corresponds to number of tracks
Good for seeing if you tend to listen deeply to specific artists or broadly across many


Popularity vs Track Ranking Scatter Plot

Compares your personal preferences against global popularity
Reveals if you tend to favor mainstream hits or more niche tracks
Trend line shows correlation between your taste and global trends
Different colors for different artists show if certain artists consistently rank differently


Album Release Timeline

Shows the release dates of albums in your top tracks
Reveals if you prefer newer or older music
Circle size shows number of tracks from each album
Colors indicate different artists to show temporal patterns in your artist preferences

Would you like me to explore any of these concepts further or suggest additional visualization approaches? For example, we could create:

A genre distribution chart
A listening time distribution (if you have that data)
An artist collaboration network
A seasonal listening pattern visualization









OFFTOPIC https://akirodic.com/p/jellyfish/
