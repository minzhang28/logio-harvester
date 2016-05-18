# logio-harvester
Docker Image for Logio Harvester

# Usage
`docker run -d -v ${host_config_path}:/home/logio/.log.io -v ${host_log_path}:${log_path} -name logio-harvester minzhang/logio-harvester`

#### This image is build on top of Alpine Linux, total size is only 86 MB
#### Please refer to http://logio.org/ for more detail information
