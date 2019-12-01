# license-checker
Checks if a particular manga is licensed in English by looking it up on a given set of sites. The user interface is a Discord bot.
## Dependencies
* Python 3.7.3+ with libraries below
	* numpy
	* discord.py
	* tensorflow
	* selenium
	* requests (should come with discord.py) TODO check if this is actually used anymore
	* aiohttp (probably come with discord.py?)
	* beautifulsoup4
* Firefox
* [geckodriver](https://github.com/mozilla/geckodriver/releases)
## Setup
* Replace the `python3.7` in the first lines of similarity.py and main.py with whatever your python command is
* Execute `./similarity.py < test_sim.txt` to cache and test the tensorflow module (might take a while to download)
* Create bot-token.txt and put your token in there
## Running
* Execute `./main.py`
* Give the Discord bot commands of the form `.lc "author" "title"` or `.lc -a author -t title`
## Sites and status
* [2DMarket](http://2d-market.com/): Works in progress. Requires site login to search.
* [Comic Bavel](https://comicbavel.com/): No English version exists.
* Comic Europa: Official site possibly [here](http://comicbavel.com/europa/)? No English versions though.
* Comic Hana-Man: Published through [Wanimagazine](https://www.wani.com/) which has no English site.
* Comic Kairakuten: Published through [Wanimagazine](https://www.wani.com/) which has no English site.
* Comic Kairakuten Beast: Published through [Wanimagazine](https://www.wani.com/) which has no English site.
* Comic Koh: Can't find official site?
* Comic Shitsurakuten: Published through [Wanimagazine](https://www.wani.com/) which has no English site.
* Comic X-Eros: Published through [Wanimagazine](https://www.wani.com/) which has no English site.
* [Fakku](https://www.fakku.net/): Work in progress.
* Girls forM: Can't find official site?
* Hana-Man Gold: Published through [Wanimagazine](https://www.wani.com/) which has no English site.
* [Project Hentai](https://www.projecthentai.com/); work in progress.
* ENSHODO: Closed permanently. [Source](https://www.twipu.com/patinafinish/tweet/1167021110849703937)
## Examples
TODO
