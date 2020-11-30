# heroku-buildpack-ffmpeg-latest

Push: [![Test](https://github.com/khlam/heroku-ffmpeg/workflows/Test/badge.svg?branch=master&event=push)](https://github.com/khlam/heroku-ffmpeg/actions?query=workflow%3ATest+event%3Apush+branch%3Amaster)  
Scheduled: [![Test](https://github.com/khlam/heroku-ffmpeg/workflows/Test/badge.svg?branch=master&event=schedule)](https://github.com/khlam/heroku-ffmpeg/actions?query=workflow%3ATest+event%3Aschedule+branch%3Amaster)

A Heroku buildpack for ffmpeg that always downloads the latest [static build](http://johnvansickle.com/ffmpeg/).

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/khlam/heroku-ffmpeg.git
```

Or run the following from the heroku command line:
```
heroku buildpacks:add https://github.com/khlam/heroku-ffmpeg.git
```
