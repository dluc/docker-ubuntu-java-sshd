## Installation

* Install Docker

* Download build from Docker Hub Registry: `docker pull dluc/ubuntu-java-sshd`

## Usage

`docker run -d --name ubuntu-java-sshd dluc/ubuntu-java-sshd`

`ssh root@$(docker inspect -f '{{ .NetworkSettings.IPAddress }}' ubuntu-java-sshd)`

The default password for root is `root`

## License

> **Note: Java provided by Oracle**
> To use the image, you must accept the [Oracle Binary Code License Agreement][1] for Java SE.

[1]: [http://www.oracle.com/technetwork/java/javase/terms/license/index.html]
