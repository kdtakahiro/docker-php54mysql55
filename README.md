# docker-php54mysql55

## requirement

__[Docker CE for Mac(Stable)](https://store.docker.com/editions/community/docker-ce-desktop-mac)__

I've tested in below.

Client:
 Version:      17.06.0-ce
 API version:  1.30
 Go version:   go1.8.3
 Git commit:   02c1d87
 Built:        Fri Jun 23 21:31:53 2017
 OS/Arch:      darwin/amd64

Server:
 Version:      17.06.0-ce
 API version:  1.30 (minimum version 1.12)
 Go version:   go1.8.3
 Git commit:   02c1d87
 Built:        Fri Jun 23 21:51:55 2017
 OS/Arch:      linux/amd64
 Experimental: true

## Usage

### Run(=up)
```
$ docker-compose up -d
```

### Create web contents.
Edit files in data/htdocs.
data/htdocs is the apache DocumentRoot.

### Into container
```
$ docker exec -ti <container name> bash
```

### Stop(=down)
```
$ docker-compose down -v
```

## License
MIT
