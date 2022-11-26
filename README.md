# docker-funkey
You must then build the docker image (don't forget the final dot!):
```bash
$ docker build -t funkeyfunkey-os .
```

### Build the disk image & firmware update files
You may now build your FunKey with:
```bash
$ docker run -it --name funkey-os funkey/funkey-os sh --privileged=True
```

