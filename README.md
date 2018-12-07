# Introduction

Docker image for [BIRT](https://www.eclipse.org/birt/)

## Usage

```sh
docker run -it --rm -p 8081:8080 -v $HOME/eclipse-workspace/LearningReporting:/var/lib/birt_reports fhalim/birt-server
```
