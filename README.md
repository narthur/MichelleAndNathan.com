# MichelleAndNathan.com

Wedding website

## Content

- Home
  - Countdown
- Our Story
  - Photos
- The Details
  - Contact information
  - ASL interpretation information
  - Map
  - Address
- Registry
- RSVP
  - [RSVP form](https://support.google.com/docs/answer/2839588?hl=en)
    - Name
    - Email
    - Coming or not
    - Note about potluck signup
    - Wishes

## URLs

URL              | Notes
-----------------|--------------
`localhost:4000` | Jekyll site

## Commands

Command                                                     | Notes
------------------------------------------------------------|------------------------------------
`docker-compose up -d --baseurl /`                          | Spin up site
`docker-compose exec site jekyll build --baseurl /`         | Rebuild site
`docker-compose exec site jekyll build --watch --baseurl /` | Watch for changes

## Info

- [jekyll-docker](https://github.com/envygeeks/jekyll-docker/blob/master/README.md)
- [jekyll/minima](https://github.com/jekyll/minima)