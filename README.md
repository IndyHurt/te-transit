# te-transit
Simple visualization of OpenStreetMap transit lines that need colors to encourage edits.

* http://indyhurt.github.io/te-transit

## Parts

* Blog post - [index.html](index.html)
* Small map for blog post - [transit/embed.html](transit/embed.html)
* Big map - [transit/index.html](transit/index.html)
* Scene file (powers the map) - [map/transit.yaml](map/transit.yaml#L698-L747)
* Map interactivity - [map/main.js](map/main.js)

### To run locally:

Download this repo, then start a web server in its directory:

    python -m SimpleHTTPServer 8000
    
If that doesn't work, try:

    python -m http.server 8000
    
Then navigate to: [http://localhost:8000](http://localhost:8000)
