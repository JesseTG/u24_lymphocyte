Bootstrap: docker
Registry: nvcr.io
Namespace: nvidia
From: theano:18.06

Username: '$oauthtoken'

%help
Example Singularity image.  You will need to provide an API key through the
environment variable SINGULARITY_DOCKER_PASSWORD.  If building this image with
sudo, remember to preserve that environment variable with `sudo -E`.

%post
    apt-get update
    apt-get dist-upgrade -y
    apt-get autoremove -y
    apt-get clean

%labels
    Author Jesse Talavera-Greenberg