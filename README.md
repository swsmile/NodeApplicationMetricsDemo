# NodeApplicationMetricsDemo
This is a demo using Application Metrics for Node.js (https://github.com/RuntimeTools/appmetrics) to monitor a Node.js application performance

In the demo, a simple Web server is set up using `express`. You could use JMeter or any other equivalent performance tools to frequently send HTTP requests to http://localhost:8082/hello to see the performance change from idle to busy state.

# Run the demo

```
# cd `NodeApplicationMetricsDemo` folder
cd NodeApplicationMetricsDemo

node main.js

# visit http://localhost:3001/appmetrics-dash/
```


