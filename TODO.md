# TODO

# v3 alpha - hitlist

# Logo

- Hire and pay (unless they donate) to get a flipping logo. The crappy orange/black thing is lame Mr Sharp.

# URLs

/ref http://www.flickr.com/photos/remysharp/6859356800/

- /latest is fixed - not redirected
- If I'm on /latest, any new updates, notify me and I can reload/live refresh if I want
- Rewind? Possibly not.

# Panels

- Options for pre-rendering
- .getCode runs through panel language
- "insertionPoint" means we can have more panels

# Save

- Add gist support back in (but do it server side) - support Lea's dabblet format (but files named jsbin.html, etc)
- Fork (as well as clone) and folk allows me to trace this heirachy of bins saved to get to this point
- Remove sha1 and move to better security

# Misc

- Include analytics for dynamic nature of JS Bin
- Libs need to support styles, etc specific to the version
- I want to monitor the keypress instead of keydown for the close window - as switch app 
- Expose API for specific tasks:
  - prefilters for panels
  - codemirror config
  - jsbin settings (key mappings?)
- Expose all the urls - via slash, but also via dot - ie. abc.js or abc.css

# IE

- Gutter is being rendered thick if the panel isn't visible - possibly solution, only render CM when made visible - problem is the .getCode won't work - so need to think about how to get around it.