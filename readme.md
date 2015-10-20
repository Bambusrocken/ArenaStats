## Guru Arena Stats

Guru Arena Stats is a custom web interface for [splewis/csgo-multi-1v1](https://github.com/splewis/csgo-multi-1v1) built in [Laravel](http://laravel.com/)
One advantage is lazy loading of Steam API Data. Because of the unreliable nature of Steam Web API, lazy loading the API data will at least load the player data from the database, while in the background sending an Ajax request for the steam data. Once this data is returned, the player page updates.