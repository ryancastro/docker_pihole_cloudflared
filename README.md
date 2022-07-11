Pihole with Cloudflared DoH, on Docker!
=============================================

### A clean docker image that has pihole, with a CloudFlared service as a DoH upstream Provider

--- 
**Goals:**
 - Use only official images
 - Use minimal config
 - Where possible, self-document
 
**Installing on Ubuntu**

Per the official PiHole repo, when using on Ubuntu, you should execute [these steps](https://github.com/pi-hole/docker-pi-hole#installing-on-ubuntu).
 
**Ways to help**
 - I'd love a clean way to use environment variable secrets (for web password) that doesn't modify the image or use docker swarm.
