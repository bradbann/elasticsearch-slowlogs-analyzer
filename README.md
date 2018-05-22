# elasticsearch-slowlogs-analyzer

Analyze Dimagi's elasticsearch slowlogs in Kibana

- Clone the repo
- `mkvirtualenv -p $(which python3) elasticsearch-slowlogs`
- `pip install -r requirements.txt`
- Move all the slowlogs you want to analyze into a folder called `input_data` in the root of this project
- `docker-compose up`
- Navigate to `127.0.0.1:5601`

There should be a few default visualizations set up. You might need to wait a few minutes for logstash to read all the data into the index.

