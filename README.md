# PiXcessPoint
RaspberryPi image to use Satellite Handset data connection on a smart phone.

## Build locally by
docker run --rm --privileged -v $PWD:/files -e PATH=/pimod:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin --workdir=/files nature40/pimod pimod.sh main.Pifile
