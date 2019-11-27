# DiscoveryAndSynchronization

## ReDoc visualization
To view an OpenAPI YAML file in ReDoc:
* Change to directory containing the YAML file (dss.yaml in this example)
* `chmod 755 dss.yaml`
* `docker run -it --rm -p 80:80 -v $(pwd)/dss.yaml:/usr/share/nginx/html/swagger.yaml -e SPEC_URL=swagger.yaml redocly/redoc`
