# HPotter Freeboard Dashboard

Freeboard is a free, open source dashboard project (https://github.com/Freeboard/freeboard) that runs locally to visualize data queried from the Hpotter-api.
The datasources are of type JSON using POST GraphQl queries.  

## Set Up
* Run hpotter_api `python3 -m hpotter_api`
* The application will be listening to localhost on the port listed in `config.yaml` in LJordan (8080 default - 8000 in the example)
* In a web browser open `localhost:<PORT>`
* Load dashboard.json file
* You can now view data in real time. Datasources refresh every 5 seconds.

## Example
![Dashboard Example](/Freeboard/DashboardPicture.jpg)