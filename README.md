# Ansible test helpers [![Container Images](https://github.com/DanNixon/ansible-testing/actions/workflows/container_images.yml/badge.svg?branch=main)](https://github.com/DanNixon/ansible-testing/actions/workflows/container_images.yml)

Common test helpers for Ansible/Molecule/GitHub Actions.

Currently includes:

- [An action](./actions/test_role) for testing roles inside of collections
- [An action](./actions/lint) for running Ansible Lint on an entire repository
- Container images for [Ubuntu](./Containerfile.ubuntu) and [Arch](./Containerfile.archlinux) used for Molecule testing of roles
