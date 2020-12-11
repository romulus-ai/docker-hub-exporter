# Metrics

Below are an example of the metrics as exposed by this exporter. 

```
# HELP docker_hub_image_is_automated docker_hub_exporter: Docker Image Is Automated.
# TYPE docker_hub_image_is_automated gauge
docker_hub_image_is_automated{image="grafana",user="grafana"} 0
# HELP docker_hub_image_last_updated docker_hub_exporter: Docker Image Last Updated
# TYPE docker_hub_image_last_updated gauge
docker_hub_image_last_updated{arch="amd64",digest="sha256:f129cbbe45d1af23d13cb3ba4cbb1fd6f5d937af4880de9a61e8e6c7d548184e",image="grafana",os="linux",tag="latest",user="grafana"} 1.6075895906982489e+09
docker_hub_image_last_updated{arch="arm",digest="sha256:2ef7305c4e686c55d727c60f5dc65663b37893d89721fc75625822d64a2c94e5",image="grafana",os="linux",tag="latest",user="grafana"} 1.607589590944767e+09
docker_hub_image_last_updated{arch="arm64",digest="sha256:b4259ea490669ebea6173962fa932d2ecc8f0d3d845b82b4f3740cbb22b60f57",image="grafana",os="linux",tag="latest",user="grafana"} 1.60758959081038e+09
# HELP docker_hub_image_pulls_total docker_hub_exporter: Docker Image Pulls Total.
# TYPE docker_hub_image_pulls_total counter
docker_hub_image_pulls_total{image="grafana",user="grafana"} 1.828134505e+09
# HELP docker_hub_image_size docker_hub_exporter: Docker Image Size.
# TYPE docker_hub_image_size gauge
docker_hub_image_size{arch="amd64",digest="sha256:f129cbbe45d1af23d13cb3ba4cbb1fd6f5d937af4880de9a61e8e6c7d548184e",image="grafana",os="linux",tag="latest",user="grafana"} 6.1074701e+07
docker_hub_image_size{arch="arm",digest="sha256:2ef7305c4e686c55d727c60f5dc65663b37893d89721fc75625822d64a2c94e5",image="grafana",os="linux",tag="latest",user="grafana"} 5.0625677e+07
docker_hub_image_size{arch="arm64",digest="sha256:b4259ea490669ebea6173962fa932d2ecc8f0d3d845b82b4f3740cbb22b60f57",image="grafana",os="linux",tag="latest",user="grafana"} 5.076422e+07
# HELP docker_hub_image_stars docker_hub_exporter: Docker Image Stars.
# TYPE docker_hub_image_stars gauge
docker_hub_image_stars{image="grafana",user="grafana"} 1709
# HELP docker_hub_image_status docker_hub_exporter: Docker Image Status.
# TYPE docker_hub_image_status gauge
docker_hub_image_status{arch="amd64",digest="sha256:f129cbbe45d1af23d13cb3ba4cbb1fd6f5d937af4880de9a61e8e6c7d548184e",image="grafana",os="linux",tag="latest",user="grafana"} 1
docker_hub_image_status{arch="arm",digest="sha256:2ef7305c4e686c55d727c60f5dc65663b37893d89721fc75625822d64a2c94e5",image="grafana",os="linux",tag="latest",user="grafana"} 1
docker_hub_image_status{arch="arm64",digest="sha256:b4259ea490669ebea6173962fa932d2ecc8f0d3d845b82b4f3740cbb22b60f57",image="grafana",os="linux",tag="latest",user="grafana"} 1
```