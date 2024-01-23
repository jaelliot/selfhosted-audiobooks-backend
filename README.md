# Audiobookshelf Backend Server

This repository contains the backend server setup for Audiobookshelf, which will serve as the backend to a mobile app that's currently in development.

## File Structure

```
.
├── LICENSE
├── Playbooks
│   ├── Docker
│   │   └── audiobookshelf_docker.yml
│   └── Vagrant
│       ├── audiobookshelf_direct.yml
│       └── inventory.ini
└── README.md
```

3 directories, 5 files

## Usage

This setup allows you to deploy Audiobookshelf either directly on a Vagrant provisioned Ubuntu 22.04 VM or within a Docker container. Choose the playbook that suits your deployment strategy:

- Use `Playbooks/Docker/audiobookshelf_docker.yml` for deploying with Docker.
- Use `Playbooks/Vagrant/audiobookshelf_direct.yml` along with `Playbooks/Vagrant/inventory.ini` for deploying on a Vagrant provisioned VM.

## Contributors

Please see the [CONTRIBUTORS.md](CONTRIBUTORS.md) file for information on how to contribute to this project.

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file.

## Acknowledgments

This backend setup is a part of a larger ecosystem focused on delivering an exceptional audiobook listening experience through our mobile app. The mobile app is currently in development and aims to provide a seamless, user-friendly interface for accessing a wide range of audiobook content.
