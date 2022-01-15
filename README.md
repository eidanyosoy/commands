## Commands I Need Alot

###### Find and Delete Empty Folders in Directory
`sudo find . -type d -empty -delete`

###### Change Directory to Downloads
`cd /mnt/downloads/books`
`cd /mnt/downloads/tv`
`cd /mnt/downloads/music`
`cd /mnt/downloads/4kmovies`
`cd /mnt/downloads/movies`

###### Login to Docker Hub
`sudo docker login`

###### Run Plex Trakt Sync
`cd /opt/appdata/plextraktsync`

`sudo docker-compose run --name traktsync -d --rm plextraktsync`

###### Run Dock Server
`sudo dockserver`

###### Change Owner Permissions Recursively From root to abc
`sudo chown -cR 1000:1000 /opt/appdata`

###### Give Directory Read/Write Permissions
`sudo chmod -R 0777 /opt/appdata`

###### Run docker-compose.yml Detached
`sudo docker-compose up -d`

###### Restart Docker
`sudo docker restart $(sudo docker ps -a -q)`
