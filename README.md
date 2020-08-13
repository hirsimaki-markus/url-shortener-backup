# url-shortener-backup

This repository is intended to act as a personal notebook about an url shortener. Anyone who feels like deciphering these notes is free to use them however they see fit under the Unlisence.

# graphic example
![](https://raw.githubusercontent.com/hirsimaki-markus/url-shortener-backup/master/url-shortener.png)

# database structure sample
```
sqlite> .schema links
CREATE TABLE links(page text primary key, links text);
sqlite> select * from links;
X|{"links": [{"url": "qwefqwef", "time": 1596898270.3786023, "desc": "wefqwef", "country": "Finland"}]}
Q|{"links": [{"url": "https://www.wikipedia.org/", "time": 1597324629.3308687, "desc": " The Free Encyclopedia", "country": "Finland"}]}
s|{"links": [{"url": "https://www.wikipedia.org/", "time": 1597325401.03812, "desc": " The Free Encyclopedia", "country": "Finland"}]}
R|{"links": [{"url": "https://github.com/hirsimaki-markus/url-shortener-backup/edit/master/README.md", "time": 1597325425.1641645, "desc": "so meta right now", "country": "Finland"}]}```
