# Official repseqio Docker image 

Run as:

```
docker run -it --rm \
    -m 1g \
    -v /path/to/data:/work \
    milaboratory/repseqio:latest \
    repseqio compile mylibrary.json mylibrary.compiled.json.gz
```

## Memory

This image does not require manual memory setting (`-Xmx...` option), if container memory limit is specified it will be automatically detected by JVM. 

## Tags

See [DockerHub page](https://hub.docker.com/r/milaboratory/repseqio) for available tags.

## License

Copyright 2019 MiLaboratory, LLC

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.