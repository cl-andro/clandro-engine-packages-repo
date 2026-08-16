# OpsPulse APT Packages Repository

This repository hosts the compiled `.deb` packages and APT index structures for **OpsPulse** (`com.clandro.b2b`).

All packages here are built using the [clandro-engine-apps-apt-repo](https://github.com/cl-andro/clandro-engine-apps-apt-repo) workflow builder.

## How to add this repository on Android:
The app's bootstrap system automatically adds this repository path upon setup. The configuration resides in `/etc/apt/sources.list.d/clandro.list`:

```apt
deb [signed-by=/data/data/com.clandro.b2b/files/usr/etc/apt/trusted.gpg.d/cl-andro.gpg] https://cl-andro.github.io/clandro-engine-apps-apt/ stable main
```
