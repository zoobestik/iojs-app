# iojs-app-tools
Simple scripts for create development containers with io.js

## Usage:
1. Build base image for containers: `./create_iojs_image iojs-app`


## More options for `create_iojs_image`
```
~ » ./create_iojs_image --help  

Usage:
    create_iojs_image [SWITCHES] [image_name='zoobestik/iojs-app']

Meta-switches:
    -h, --help                Prints this help message and quits
    -v, --version             Prints the program's version and quits

Switches:
    --directory VALUE:str     Set path to script working directory; this option keep generated files
    --docker VALUE:str        Path to docker API; the default is 'unix://var/run/docker.sock'
    -i, --iojs_ver VALUE:str  Version of io.js into container; the default is '1.0.1'
    -u, --username VALUE:str  Username for default user into container; the default is 'docker'
    --verbose                 See docker build log
```
