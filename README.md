# A lambda function for creating a webring on netlify

Add this to your netlify account, have folks add their sites to `/data/sites.json` and you're off to the races.

Each site can add a widget to their site and hit the end points `/next`, `/random` and `/previous` to send their users to a new site! A sample widget is provided at `widget.html`; just copy that into your website's code and replace the urls with your own.
