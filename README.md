# Docker LEMP stack
  - version 0.1.60416
  - codename: catcoder/lempstack
  - license: GNU GPL
  - Maintainer: Jose Luis Gomez Jaen <catcoder.php@gmail.com>

## Docker: the container engine
Docker is an open source project to pack, ship and run any application as a lightweight container.
Docker containers are both hardware-agnostic and platform-agnostic. This means they can run anywhere, from your laptop to the largest cloud compute instance and everything in between - and they don't require you to use a particular language, framework or packaging system. That makes them great building blocks for deploying and scaling web apps, databases, and backend services without depending on a particular stack or provider.

Docker began as an open-source implementation of the deployment engine which powers dotCloud, a popular Platform-as-a-Service. It benefits directly from the experience accumulated over several years of large-scale operation and support of hundreds of thousands of applications and databases.

## What is LEMP stack?
Is a docker container with the stack LEMP (Linux,Nginx,MySQL,PHP), that install an image to can generate a development environment

### USAGE
## How to use this image?
### Install Docker
You can see the installation process of your distro on: https://docs.docker.com/
## Installing the container:
Get the script repositorie
```shell
git clone git@bitbucket.org:gextech/mymbee-script.git
cd mymbee-script/
chmod +x container_up.sh
./container_up.sh
```

With this process begins the installation of the image on your system

If all works fine, you will should see this...
```shell
NOW YOU HAVE INSTALLED THE MACHINE!

Catcoder laravel
 
catcoder-laravel [ARGS]
options:
 
  -h, --help                         show brief help
  --composer-install                 Runs composer install into the remote machine
  --composer-update                  Runs composer update into the remote machine
  --laravel-migration                Runs a database migration into the remote machine
  --laravel-controller               Make a laravel controller into the source repository
  --laravel-controller-resource      Make a laravel controller into the repository, create the resource URL's and CRUD methods
  --laravel-model                    Make a laravel model into the source respository
  --laravel-model-migartion          Make a laravel model into the source respository and create the migration file
  --start                            Start the laravel machine instance
  --stop                             Stop the laravel machine instance
  --restart                          Restart the laravel machine instance
```

## Usage

After of the installation you can use the source code on the follow directory:

```shell
cd ~/docker/projects/mymbee-container/src
```
Any change on the source code will be reflected immediately on the remote machine.

# Usage

```shell
Catcoder laravel
 
catcoder-laravel [ARGS]
options:
 
  -h, --help                         show brief help
  --composer-install                 Runs composer install into the remote machine
  --composer-update                  Runs composer update into the remote machine
  --laravel-migration                Runs a database migration into the remote machine
  --laravel-controller               Make a laravel controller into the source repository
  --laravel-controller-resource      Make a laravel controller into the repository, create the resource URL's and CRUD methods
  --laravel-model                    Make a laravel model into the source respository
  --laravel-model-migartion          Make a laravel model into the source respository and create the migration file
  --start                            Start the laravel machine instance
  --stop                             Stop the laravel machine instance
  --restart                          Restart the laravel machine instance
```

# Build the container:
> The installation process has been moved to: https://bitbucket.org/gextech/mymbee-script/
