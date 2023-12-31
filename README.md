# Template

![Ansible Collection](https://img.shields.io/badge/collection-pandemonium1986.k8s__toolbox-blue?logo=ansible)
![Ansible Role](https://img.shields.io/ansible/role/36274?logo=ansible)
![Ansible Quality Score](https://img.shields.io/ansible/quality/36274?logo=ansible)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit)
![Sample workflow](https://github.com/Pandemonium1986/template/workflows/Sample%20workflow/badge.svg)![GitHub release](https://img.shields.io/github/release/Pandemonium1986/ansible-role-init.svg?logo=github)
![Github license](https://img.shields.io/github/license/Pandemonium1986/ansible-role-init.svg?logo=github)

One Paragraph of project description goes here

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```yaml
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```yaml
Give the example
```

And repeat

```yaml
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end-to-end tests

Explain what these tests test and why

```yaml
Give an example
```

### And coding style tests

Explain what these tests test and why

```yaml
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

- [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/index.html) - Provisioning
- [Vagrant](https://www.vagrantup.com/downloads.html) - To build and manage the box.
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads) - The only provider available.

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Pre Committing

This repository use [pre-commit](https://pre-commit.com) to manage commit-msg, pre-commit and pre-push hooks (if necessary).
Be sure to install them before any push.

```sh
cd MY_REPO && \
pre-commit install --hook-type commit-msg && \
pre-commit install --hook-type pre-push && \
pre-commit install
```

For more info see this [cheatsheet](https://github.com/Pandemonium1986/cheatsheet/blob/main/Commit.md)

Also every commit MUST follow the [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/).

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

- **Michael Maffait** - _Initial work_ - [Pandemonium1986](https://github.com/Pandemonium1986)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details

## Source

- [PurpleBooth/README-Template.md](https://gist.githubusercontent.com/PurpleBooth/109311bb0361f32d87a2/raw/8254b53ab8dcb18afc64287aaddd9e5b6059f880/README-Template.md/)
- [PurpleBooth/Good-CONTRIBUTING.md-template.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426)
