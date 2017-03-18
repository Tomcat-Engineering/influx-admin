# influx-admin

InfluxDB used to ship with an "admin web interface" which allowed you to test queries.  This has [now been deprecated](https://docs.influxdata.com/influxdb/v1.2/tools/web_admin/) in favour of [Chronograf](https://docs.influxdata.com/chronograf/).  

This project forks the last version of the admin web interface and adds new features like graphs.

In time, Chronograf will probably do everything that this tool can do, but for now this might be useful to some people.

## Instructions

Just host the contents of the `assets` folder using your favorite web server.

One option is to use Python's built-in web server - just run the following command from the `assets` folder:

### Python 2.x:

`python -m SimpleHTTPServer`

### Python 3.x:

`python -m http.server`

Your admin interface will then be accessible on port 8000.  Use the settings button in the top right corner to configure access to your InfluxDB instance.