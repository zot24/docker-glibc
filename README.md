# Alpine GNU C library (glibc) Docker image

This is an Alpine GNU C library (glibc) docker base image using [Alpine](http://alpinelinux.org/) Linux to support `glibc` using `C.UTF-8` locale as default and based on the [frolvlad/alpine-glibc](https://hub.docker.com/r/frolvlad/alpine-glibc/) docker image actually there is no differences so I would recommend to use [frolvlad/alpine-glibc](https://hub.docker.com/r/frolvlad/alpine-glibc/) instead I create this base image to have more control over my images.

## Getting Started

This image have been build for being used as a base image and extend it, so you'll need to extending the base image like:

```
FROM zot24/glibc
...
```

## Resources

Some util resources about docker + images + alpine + being smart :)

* [Tips & Tricks with Alpine + Docker](http://blog.zot24.com/tips-tricks-with-alpine-docker/)
* [Tips & Tricks with Docker & Docker compose](http://blog.zot24.com/tips-tricks-docker/)

## Authors

* **Israel Sotomayor** - *Initial work* - [zot24](https://github.com/zot24)

See also the list of [contributors](https://github.com/zot24/docker-glibc/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/zot24/docker-glibc/blob/master/LICENSE) file for details
