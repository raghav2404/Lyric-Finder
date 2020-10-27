Lyric Finder WebApp using ReactJS ,Context Api and Bootstrap.Displays the Top10 tracks and allows user to search for Lyrics of any song using Musixmatch Api.

https://lyricfinder-raghav24.netlify.app/


1)npx create-react-app to start 
2) Used React Router to Route between links.
3)Components:
        Navbar
        Title
        Search
        Track
        Tracks(Top 10 and currently searched)
        Lyrics
        
 4) The track and lyrics data is fetched from the Musixmatch api,authenticated using API Key using 'axios' http client to handle server requests.
 5) Used Bootstrap to style the cards and display in components,Moment to modify date in Lyrics.
 6) Context Api which keeps the state(tracks) and provider which provides track data to consumer class components.
 7) The WebApp displays the Top 10 Global Tracks. On Searching for a Song,it displays the top 10 results and on clicking the specific track,shows the lyrincs on a new page along with release date,genre and album name.
