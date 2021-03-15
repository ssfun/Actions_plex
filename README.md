# PlexTraktSync
Actions that syncs the movies, shows and ratings between trakt and Plex (without needing a PlexPass or Trakt VIP subscription)

# Secrets

| Name                  | 说明                         |
| :-------------------: | ---------------------------- |
| `SET_ENV`             |   Plex Trakt 登录信息配置文件   |
| `SET_PYTRAKT`         |   Trakt API 信息配置文件       |

## SET_ENV
```
PLEX_USERNAME=XXX
PLEX_TOKEN=XXX
PLEX_BASEURL=http://XXX:32400
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

# Thanks

[@Taxel](https://github.com/Taxel/PlexTraktSync)  - PlexTraktSync
