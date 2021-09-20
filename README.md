# OnePlus 9 LineageOS with MicroG, magisk, android auto build and install guide



# Install


# Build

TODO: bring in android auto reqs

## Prepare the build environment

First we need to build the docker image:
```
git checkout https://github.com/lineageos4microg/docker-lineage-cicd.git
cd docker-lineage-cicd
docker build --tag solidhal/docker-lineage-cicd .
```

Now head back to this checkout, and run the build script This will take quite some time, and use ~200GB of disk space. 
build_xz2_compact.sh can be modified to not include microg, signature spoofing, android auto, etc if you would prefer

```
cd build
./build_xz2_compact.sh
```


## Setup Magisk



# Thanks:
To the LineageOS devs!
