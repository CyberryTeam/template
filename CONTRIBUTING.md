# Contributing

## Table of Contents

- [Guidelines](#guidelines)
- [Getting started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Testing](#testing)

## Guidelines

We have adopted general guidelines for all our projects.
See [CyberryTeam/contributing](https://github.com/CyberryTeam/contributing) for more information.

## Getting started

### Prerequisites

1. Install `library-dev`:

- apt (Debian based distributions):

```shell script
sudo apt install library-dev
```

- dnf (Fedora based distributions):

```shell script
sudo dnf install library-dev
```

- pacman (Arch based distributions):

```shell script
sudo pacman -S library-dev
```

### Installation

1. Clone the repository:

```shell script
git clone https://github.com/username/repository.git
```

2. Setup the project:

```shell script
setup .
```

## Testing

Run the tests:

```shell script
test .
```

Run coding style tests:

```shell script
lint .
```
