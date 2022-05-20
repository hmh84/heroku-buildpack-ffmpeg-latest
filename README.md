# heroku-buildpack-ffmpeg-latest
Original Source: https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest

This repository is for my own personal use. You may use it, however it is not guarenteed that it will continue to be hosted at the same git url or download distibution url. I **strongly** suggest you either use the original, or clone your own version.

## Usage

Run the following from the heroku command line:

```
heroku buildpacks:add --index 1 https://github.com/hmh84/heroku-buildpack-ffmpeg-latest.git
```

Note: This buildpack should be added before the main language buildpack (by using `--index 1`),
since the application process types are calculated from the last buildpack in the list if no
`Procfile` is specified.
