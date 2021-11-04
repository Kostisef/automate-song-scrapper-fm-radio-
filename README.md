# automate-song-scrapper-fm-radio
Song scrapping from Online FM radio Wonder FM, using **Python** and **Selenium**.  
(_note: ChromeDriver version should match your installed Chrome Browser version_)

Just run src/main.py and every 90 seconds the code will extract current and next song in the playlist. All recordings are saved into a txt file named song_list.txt **AND** a MySQL database.

_______________________________________________________________________________________________
#### FUTURE TASKS
* GUI
_______________________________________________________________________________________________

**Format of each recording:**

* Song_title - Artist
* Youtube_search_song_url

**e.x.:**

* I Go - Peggy Gou

* https://youtube.com/results?search_query=I+Go+-+Peggy+Gou
