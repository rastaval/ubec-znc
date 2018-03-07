# ubec-znc

Run a znc bouncer on Heroku.

See the buildpack for details.

https://github.com/j-mcnally/znc-buildpak

Set the app's ngrok api key (get one from https://ngrok.com)

`heroku config:set NGROK_API_KEY=[API_KEY]`

Set the app's build pack with

`heroku config:set BUILDPACK_URL=https://github.com/j-mcnally/znc-buildpak`


copy your znc config file from ~/.znc/configs/znc.conf into your project.
# ubec-znc


