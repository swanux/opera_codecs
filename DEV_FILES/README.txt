https://www.google.com/chrome/ - 4.10.2391.0
https://github.com/iteufel/nwjs-ffmpeg-prebuilt/releases - 0.52.2
Maybe use https://repo.herecura.eu/herecura/x86_64/ - opera-beta-ffmpeg-codecs-98.0.4758.10
Update codecs from here ^

Go to BUILD/ and:
Edit changelog and control

Run:
dpkg-deb --build opera-codecs

Also update template

And test:
https://bitmovin.com/demos/drm
