# README

### Let's get started: `docker pull tychrestoff/debian`

Dockerfiles for base Debian images.

Docker Hub: https://hub.docker.com/r/tychrestoff/debian/

Includes:
  * Jessie (8.2)
  * Wheezy (7.9)
  * Squeeze (6.0)
  
Each version comes in four flavors that each build upon the last:
  * min - Only Debian. You get bash and that's about it.
  * curl - cURL! Get and send files using URL syntax.
  * scm - Supports popular source control managers.
  * fat - Save yourself from installing these dependencies for `gem`, `npm`, `pip`, etc
  
Check out the individual READMEs for each of the Dockerfiles to learn more about what the images include by default.
