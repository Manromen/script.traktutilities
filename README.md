seadog seems to continue this project. See: http://forum.xbmc.org/showthread.php?tid=139839

I stopped working on this project.
Feel free to fork and continue ...

# Trakt Utilities
Trakt Utilities is a XBMC Add-on for trakt.

This add-on give XBMC the ability to synchronise seen movies, TV shows/episodes with trakt (trakt account required).
More info about trakt: http://trakt.tv/

If you use this Addon, you no longer need the official anymore.
    
This is an open-source project.
We'll do our best, but use it at your own risk.

You can download the latest release here: https://github.com/Manromen/script.TraktUtilities/wiki/Download

**ATTENTION:**
This Add-on needs library mode. All Movies / TV Shows, that are not in library mode will be ignored.

## Service Based Features:
* Automatic updates on start-up
* Rating dialog after watching movies or TV episodes

## Menu Based Features:
* Watchlist
    * Watchlist Movies
        - Shows your current watchlist
        - Each movie has a thumbnail and background image
        - Tags on the thumbnail indicate whether you have got a local copy of the movie
        - Selecting a movie will play it locally

    * Watchlist TV Shows
        - Shows your current watchlist
        - Each show has a thumbnail and background image

* Friends  
    Coming soon, watch this space  
    Currently able to list your friends and indicate what they are currently watching  
    * Currently watching
    * Watch-list
    * Watched
    * Profile

* Recommendations
    * Recommended Movies
        - Shows a list of movies that trakt thinks you will like
        - Each movie has a thumbnail and background image
        - Tags on the thumbnail indicate whether you have got a local copy of the movie
        - Tags on the thumbnail indicate whether the movie is in your watchlist
        - Selecting a movie will play it locally
        
    * Recommended TV Shows
        - Shows a list of TV shows that trakt thinks you will like
        - Each show has a thumbnail and background image

* Trending
    * Trending Movies
        - Shows a list of movies that are trending on trakt
        - Each movie has a thumbnail and background image
        - Tags on the thumbnail indicate whether you have got a local copy of the movie
        - Selecting a movie will play it locally
        
    * Trending TV Shows
        - Shows a list of TV shows that are trending on trakt
        - Each show has a thumbnail and background image

* Update / Sync / Clean 
    * Update Movie Collection:
        - updates your trakt movie library (not the seen movies) with your xbmc collection
        
    * Sync seen Movies:
        - synchronise seen movies between xbmc and trakt
        - seen movies from xbmc will be set as seen on trakt
        - seen movies from trakt will be set as seen on xbmc
        - it don't sets movies as unseen
        
    * Update TV Show Collection:
        - same like Update Movie Collection, but for TV Shows.
            
    * Sync seen TV Shows:
        - same like Sync seen Movies, but for TV Shows.
            
    * Clean Movie Collection:
        - this will remove deleted movies from the trakt collection (unlibrary, it will not set movies as unseen).  

             **ATTENTION:**  
        - don't use this function, if you collect data about your DVDs, Blu-Rays, etc.  
        - this will unlibrary all movies on tract, that are not in the xbmc database
        
    * Clean TV Show Collection:
        - same like Clean Movie Collection, but for TV Shows  

            **ATTENTION:**  
        - don't use this function, if you collect data about your DVDs, Blu-Rays, etc.  
        - this will unlibrary all tvshows on trakt, that are not in the xbmc database

The Utilities for TV Shows only work, if your scraper is TVDB ([[http://thetvdb.com/]]).

Special Thanks to: Justin Nemeth and Sean Rudford, for the great trakt project.
