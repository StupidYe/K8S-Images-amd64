FROM mongo
MAINTAINER 337823332@qq.com

COPY apis/example.json /init.json
CMD mongoimport --host janus-database --db janus --collection api_specs --type json --file /init.json --jsonArray