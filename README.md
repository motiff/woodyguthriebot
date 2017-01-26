#Mujeres Libres

###Built With
* [Node.js] (https://nodejs.org/en/)
* [Discord.js] (https://www.npmjs.com/package/discord.js)
* [Feedparser] (https://www.npmjs.com/package/feedparser)
* [Request] (https://www.npmjs.com/package/request)
* [striptags] (https://www.npmjs.com/package/striptags) - To remove HTML from feeds
* [entities] (https://www.npmjs.com/package/entities) - To remove HTML entities from feeds
* [moment-timezone] (https://www.npmjs.com/package/moment-timezone) - For customizable timezones per guild
* Datebase Manager (choose one)
 * [sqlite3] (https://www.npmjs.com/package/sqlite3) (recommended)
 * [mysql] (https://www.npmjs.com/package/mysql)

##Commands

[`rssadd`]: Add feeds for that specific channel. `(prefix)rssadd rss_link_here`. A new entry will be made in config.json with its name in the format of channelID_feedLink, and will use the default message formatting unless customized otherwise.

[`rssremove`]: To remove feeds. After menu selection, the feed will automatically be removed from config.json.

[`rssmessage`]: Set the custom text message of the feed that will be sent.

[`rssembed`]: Enable and set embed properties to be sent in addition to its regular message.

[`rssfilteradd`]: Add filters for specific categories for a feed.

[`rssfilterremove`]: Remove filters for specific categories for a feed.

[`rsstimezone`]: Add a timezone to be applied for {date} tags in all feeds for the server.

[`rsstest`]: Print out the properties for that specific RSS feed and its filter status on whether it passed (if filters exist), along with a randomly chosen feed of any age - in the defined message/embed format in config.json. 
