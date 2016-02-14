# Install Docker on Mac

Author: Lin Dong

Date: Sat Feb 13 16:12:31 PST 2016

## Instruction

1. Download [DockerToolbox-1.10.1.pkg](https://github.com/docker/toolbox/releases)
2. `eval "$(docker-machine env default)"`
3. `docker run -d -p 3000:3000 unclebarney/chit-chat`
4. Run `docker-machine stop` to shutdown VM
5. Read the [doc](https://docs.docker.com/machine/get-started/)
