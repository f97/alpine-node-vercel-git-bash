# Node.js with Git Dockerfile

A minimal Dockerfile based on Node.js 16 LTS (Gallium), Node.js 18 LTS (Hydrogen) or Node.js 20 (Iron) alpine with Git and ssh installed.

## What's included

- Node.js 16 LTS (Gallium), 18 LTS (Hydrogen) or 20 (Iron)
- npm 8 (Node.js 16) or npm 9 (Node.js >= 18)
- yarn
- git
- bash

### Available platforms

These Dockerfiles leverage the new `buildx` functionality and offer the following platforms:

- linux/amd64
- linux/arm64
- linux/arm/v7
- linux/arm/v6
- linux/ppc64le
- linux/s390x

---

Built by (c) f97 and contributors. Released under the MIT license.
