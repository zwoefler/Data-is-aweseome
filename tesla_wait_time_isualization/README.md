# Tesla Delivery Visualizer


## Scope
Collect all available Tesla Model data form the WaybackMachine.
Why?
- I don't need to build infrastructure to collect the data daily
- WaybackMachine has sufficient data
- Standardises the data gathering process
- Can still add it later on

## Info on used data
Our data is not 100% accurate and provides a trend overview, not a detailed analysis!
We gathered the data using the WebArchive and every single entry per tesla webpage for model and location.

The data is therefore offset to more recent dates, since the Webarchive
scrapped the webpages more frequently in recent times.
We cut out duplicate days and chose the first entry for a duplicate day.

A jump up in price on a specific date might have occured a few days before or after.
