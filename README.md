# PlexTraktSync
Actions that syncs the movies, shows and ratings between trakt and Plex (without needing a PlexPass or Trakt VIP subscription)

# Secrets

| Name                  | 说明                         |
| :-------------------: | ---------------------------- |
| `SET_ENV`             |   Plex Trakt 登录信息配置文件   |
| `SET_PYTRAKT`         |   Trakt API 信息配置文件       |
| `SET_CONFIG`         |    Plex Trakt 同步信息配置文件   |

## SET_ENV
```
PLEX_USERNAME=XXX
PLEX_TOKEN=XXX
PLEX_BASEURL=http://XXX:32400
PLEX_FALLBACKURL=http://localhost:32400
TRAKT_USERNAME=XXX
```

## SET_PYTRAKT
```
{
"CLIENT_ID": "XXX",
"CLIENT_SECRET": "XXX",
"OAUTH_TOKEN": "XXX",
"OAUTH_REFRESH": "XXX",
"OAUTH_EXPIRES_AT": XXX
}
```

## SET_PYTRAKT
```
{
    "log_debug_messages": false,
    "logging": {
        "append": false
    },
    "sync": {
        "liked_lists": true,
        "watchlist": true,
        "watched_status": true,
        "collection": true,
        "ratings": true
    },
    "xbmc-providers": {
        "movies": "imdb",
        "shows": "tvdb"
    },
    "excluded-libraries": [
        "Private",
        "Family Holidays"
    ]
}
```

# Thanks

[@Taxel](https://github.com/Taxel/PlexTraktSync)  - PlexTraktSync
