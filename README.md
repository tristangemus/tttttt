# wordpress-docker-starter

This repo is a quick starter project for local dev environments for Wordpress with docker.

I needed this to quickly spin up local instances without much fuss but with some extras when dealing with third-party sites which have no CI or any workflow in place.
## Quick start

- Run with `docker-compose up -d`
- Add `127.0.0.1 wordpress.local` on your `/etc/hosts` file
- Access your site on https://wordpress.local, install as normal if you get the install prompt
- Install your favourite backup/restore plugin and run a database/file import on the newly installed Wordpress0 (optional) 
