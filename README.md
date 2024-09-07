## Goals

The goal of the project is to try out some testing methods and tools, there are
no special plans for development.

Progress can be tracked in [TODO.md](TODO.md).

## Problems

Service/application to solve specific problems:

- TOP N streamers per category (viewers, online time, frequency). User able to
select category, we create special background task.
- Get link to VOD/VOD's/Stream and watch it, embed?
- Get channel information, channel emotes, rich game details, etc.

## Technical requirements

- User's authorization
- User's access rights
- External APIs integration and testing
- Twitch rate limit is 800 requests/minute

## Resources

- https://realpython.com/flask-connexion-rest-api/
- https://github.com/Teekeks/pyTwitchAPI/blob/master/twitchAPI/twitch.py
- https://docs.sqlalchemy.org/en/20/orm/dataclasses.html
- https://flask.palletsprojects.com/en/3.0.x/quickstart/
- https://dev.twitch.tv/docs/api/reference/#search-channels
- https://dev.twitch.tv/docs/api/reference/#search-categories
- https://dev.twitch.tv/docs/api/reference/#get-streams
- https://dev.twitch.tv/docs/api/reference/#get-games
- https://dev.twitch.tv/docs/api/reference/#get-channel-emotes
- https://dev.twitch.tv/docs/api/reference/#get-channel-information
- https://api-docs.igdb.com/
- https://grafana.com/grafana/dashboards/4279-rabbitmq-monitoring/

## Dependencies

- sqlite

- aio-pika
- flask
- flask-sqlalchemy
- dpath-python
- cattrs
- attrs
- pytest
- pytest-recording

- react
- vite
