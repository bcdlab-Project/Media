# Media
### Repository to store common Project Media

## Naming Scheme
The naming scheme for media files is as follows:
```
[name]-[color/white/black/etc]-[type]-[format (if applicable) ]
```

## Console Media
The console media creation is done using [jp2a](https://github.com/cslarsen/jp2a).
The command used to convert an image to ASCII is:
```bash
jp2a --output=[media name]-ascii.txt --colors [media name] --height=[height]
```
Normaly Console Media is Stored in the `console` folder.

> Note: Some Console Media ware Edited by hand to make them look better.