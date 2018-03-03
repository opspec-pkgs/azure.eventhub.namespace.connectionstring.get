[![Build Status](https://travis-ci.orgthub.namespace.connectionstring.get.svg?branch=master)](https://travis-ci.orgthub.namespace.connectionstring.get)

<img src="icon.svg" alt="icon" height="100px">

# Problem statement

gets an azure eventhub connection string

# Format

this version of the pkg is in [![opspec 0.1.5](https://img.shields.io/badge/opspec-0.1.5-brightgreen.svg?colorA=6b6b6b&colorB=fc16be)](https://opspec.io/0.1.5/packages.html) format

# Example usage

## Install

```shell
opctl pkg install azure.eventhub.namespace.connectionstring.get#2.0.0
```

## Run

```
opctl run azure.eventhub.namespace.connectionstring.get#2.0.0
```

## Compose

```yaml
op:
  pkg: { ref: azure.eventhub.namespace.connectionstring.get#2.0.0 }
  inputs:
    subscriptionId:
    loginId:
    loginSecret:
    loginTenantId:
    authRule:
    name:
    namespace:
    resourceGroup:
    # params w/ default
    authRuleKey:
    loginType:
  outputs:
    connectionString:
```

# Support

join us on
[![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or
[open an issue](https://azure.eventhub.namespace.connectionstring.get/issues)

# Releases

releases are versioned according to
[![semver 2.0.0](https://img.shields.io/badge/semver-2.0.0-brightgreen.svg)](http://semver.org/spec/v2.0.0.html)
and [tagged](https://git-scm.com/book/en/v2/Git-Basics-Tagging); see
[CHANGELOG.md](CHANGELOG.md) for release notes

# Contributing

see
[project/CONTRIBUTING.md](https://github.com/opspec-pkgs/project/blob/master/CONTRIBUTING.md)
