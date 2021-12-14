# HW Report

Deploy the demo in Docker

![set-up](screenshots/1-set-up.png)

Create the necessary connectors by running a script

![create-connectors](screenshots/2-create-connectors.png)

Sample data from generators

![data-sample](screenshots/3-data-sample.png)

See the connectors on WEB UI at http://localhost:9021/

![web_ui](screenshots/4-web-ui-connectors.png)

Create streams by running a script

![create_streams](screenshots/5-create-streams.png)

View the flow in WEB UI

![streams_flow](screenshots/6-streams-flow.png)

Query some stream to verify the data

![query](screenshots/7-query-to-verify.png)

Send data to Grafana and create a dashboard via scripts

![to_grafana](screenshots/8-send-to-grafana.png)

View the dashboard in Grafana at http://localhost:3000/

![query](screenshots/9-dashboard.png)

See that additional Elasticsearch connectors have been created

![new_connectors](screenshots/10-new-connectors.png)

Emulate sessionizing the data and view the effects in Grafana

![sessionized](screenshots/11-sessionized.png)