![alt text](http://dnorthrupga.com/assets/web_banner_resize.png "Northrup Consulting")

Steam Sale Parser
======

The purpose of this is to parse through Rhekua's Site (temporary), check the current price, store it if lower than before, and then save it to MySQL.
The other half of the project is leveraging the Ang4 site to allow people to 'watch' games, get recommendations and receieve texts (Twilio or GV API) when a game they want is on sale.

## Usage

Create a 'dbconfig.py' file with your DB credentials. Format should match standard Py config
```python
mysql = {'host':'localhost',
         'db':'a_cool_db',
         'user':'super_cool_user',
         'passwd':'super_cool_password'}
```
## Contributing

Fork it!
Create your feature branch: git checkout -b my-new-feature
Commit your changes: git commit -am 'Add some feature'
Push to the branch: git push origin my-new-feature
Submit a pull request :D

## History

2017-07-15: Modified it from being a CSV output to using MySQL for injestion! * ~~ :heart:
   * Can only go :point_up: from here folks!

## Credits

+ The amazing team over at [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) - Making scraping easier than ever.
+ Rhekua for hosting [Rhekua - SteamSales](http://steamsales.rhekua.com/) - Used it for years, and now giving me a good playground to test with prior to integrating the API
+ Much patience, and a standing desk. Didn't want any (╯°□°)╯︵ ┻━┻ going on

## License

MIT 2017
