# Docker Symfony

A docker project for Symfony projects!

Based on
* https://garyclarketech.teachable.com/p/learn-docker-and-php
* https://github.com/GaryClarke/docker-php/tree/symfony-version 
* https://www.youtube.com/watch?v=qv-P_rPFw4c
* https://garyclarketech.teachable.com/p/home?referral_code=I7T5DF

## Setup
- For a standard build / setup, simply run `docker compose up -d `.
- For a development build (which exposes DB ports and includes Xdebug), run `sh ./bin/dev-mode.sh -d`
- To run with Xdebug enabled, run `XDEBUG_MODE=debug sh ./bin/dev-mode.sh -d --build`



