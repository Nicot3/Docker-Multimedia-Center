# Docker Multimedia Center
A simple way to run a complete multimedia center with easy downloads.

### Requirements 
* Docker
* Docker Compose


> Is not necessary to specify the tag, the arch will be selected automatically.
### Containers

* Plex (Multimedia center)
* Jackett (Indexer for torrent websites)
* Radarr (Tracker for Movies)
* Sonarr (Tracker for TV Shows)
* Lidarr (Tracker for Music)
* Ombi (Request manager for Movies, TV Shows & Music)

## 0. Installation

First of all, you need to check if your architecture is compatible. This is the current supported archs:
* x86-64
* arm64
* armhf

If your architecture is compatible, then start with the installation.

1. Create `.env` file. You can rename `.env.sample` and edit as you need. See the [wiki page](https://github.com/Nicot3/DockerMediacenter/wiki/The-.env-file) for understanding every variable.
2. Run everithing with `docker-compose up`
3. Done! Everything will be running


## 1. Configuration

If you want to know how to configure every container, read the wiki page for every container.

Follow these steps for a easy configuration.

1. Configure Jackett with your trackers. [See configuration Page](https://github.com/Nicot3/DockerMediacenter/wiki/Jackett-configuration)
2. Configure Radarr/Sonarr/Lidarr. [See configuration Page](https://github.com/Nicot3/DockerMediacenter/wiki/Radarr-Sonarr-Lidarr-configuration)
3. Configure Plex Server. [See configuration Page](https://github.com/Nicot3/DockerMediacenter/wiki/Plex-configuration)
4. Configure Ombi. [See configuration Page](https://github.com/Nicot3/DockerMediacenter/wiki/Ombi-configuration)

> Is higly recommended to follow this steps in order for an easy setup.

## 2. Issues
If you have some error that you don't know how to solve, need help or have some idea to the project, [Send an issue](https://github.com/Nicot3/DockerMediacenter/issues).

## 3. Contributing

If you want to contribute, clone the project, make your changes and [submit a pull request](https://github.com/Nicot3/DockerMediacenter/compare). 

> The changes that modify the configuration adapted to an especific user will be rejected.