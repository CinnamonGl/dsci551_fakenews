# dsci551_fakenews

### Install
This project uses [pyrebase](https://github.com/nhorvath/Pyrebase4) and [schedule](https://schedule.readthedocs.io/en/stable/). Go check them out if you don't have them locally installed.

### Outline
From news website homepage, it crawls all news address. Next, for each news address, it extracts 'title', 'author', 'text' and 'url' four features, then sends features to cloud database, with recording in newsURLs.csv. Above process is executed every 30 minutes, to enable data flow from news websites to the cloud database.
