# docker-ibmcloud

The easiest way to try the IBM Cloud CLI on your laptop!

## How to build

```bash
docker build --rm -t vitaled/docker-ibmcloud -f ibmcloud/Dockerfile .
```

## How to run

```bash
docker run -ti vitaled/docker-ibmcloud /bin/sh
```

You can then you use your IBM Cloud Credentials to login:

```sh
$ ibmcloud login
```

## Resources

[IBM Cloud registration page](https://console.bluemix.net/registration/)