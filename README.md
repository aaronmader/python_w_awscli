# python_w_awscli

Dockerfile to build the docker image: python_w_awscli
(This'll help shave a few seconds off your build pipeline.)

```bash
FROM python
RUN pip install awscli
```

see: https://hub.docker.com/r/aaronmader/python_w_awscli/
and: https://github.com/aaronmader/python_w_awscli
