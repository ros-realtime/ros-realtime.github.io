# ROS 2 Real-Time Working Group Documentation

This repository contains the sources for the ROS 2 real-time working group documentation that is hosted at https://ros-realtime.github.io/.
The sources from this repository are automatically fetched and built on every commit.

## Contributing to the documentation

Contributions to this site are most welcome.
Please be sure to read the below sections carefully before contributing.

The site is built using [Sphinx](https://www.sphinx-doc.org/)

### Branch structure

This repository is setup with one branch per ROS 2 distribution to handle differences between the distributions.
If a change is common to all ROS 2 distributions, it should be made to the `rolling` branch (and then will be back-ported as appropriate).
If a change is specific to a particular ROS 2 distribution, it should be made to the respective branch.

### Source structure

The source files for the site are all located under the `source` directory.
The root directory contains configuration and files required to locally build the site for testing.

### Building the site

To build the site for just this branch, type the following commands at the top-level of the repository.

```bash
cd ~
git clone https://github.com/ros-realtime/ros-realtime.github.io
cd ros-realtime.github.io
docker build -t ros-realtime.github.io .
docker run -v "$(pwd)":/docs -u $(id -u):$(id -g) -it ros-realtime.github.io
```

Build results are located at `~/ros-realtime.github.io/build/index.html`.
This is the recommended way to test out local changes.

### Runnining the site

To run the site locally, type the following commands at the top-level of the repository.

```bash
cd build
python3 -m http.server --bind 127.0.0.1
```

It will be accessible remotely at http://<remote_ip_address>:8000

## Contributing to ROS 2 real-time working group

To contribute to the project please refer to the [How to Contribute](https://ros-realtime.github.io/Contributing/how_to_contribute.html).
