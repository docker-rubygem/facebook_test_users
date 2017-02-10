[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/facebook_test_users.svg)](https://hub.docker.com/r/rubygem/facebook_test_users/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/facebook_test_users.svg)](https://hub.docker.com/r/rubygem/facebook_test_users/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/facebook_test_users.svg)](https://hub.docker.com/r/rubygem/facebook_test_users/)
[![Gem Downloads](https://img.shields.io/gem/dt/facebook_test_users.svg)](https://rubygems.org/gems/facebook_test_users/)
# facebook_test_users

Auto-Generated Docker image for facebook_test_users to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/facebook_test_users`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/facebook_test_users`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/facebook_test_users`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/facebook_test_users/)
