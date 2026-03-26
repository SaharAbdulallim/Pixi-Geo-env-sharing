# Pixi-Geo-env-sharing

### This repo is for sharing Pixi geospatial env for different OS, like if you want to run the same env from Linux/macOS to Windows.

## Instructions:
To share your environment, first commit pixi.toml and pixi.lock to version control:
```
git add pixi.toml pixi.lock
git commit -m "Add Pixi project configuration and lock file"
git push
```
 

After this, you can reproduce the environment on another machine:
```
git clone <your-repo-url>
cd <your-project-folder>
pixi install
```

#### Source:
[Pixi: how to start](https://www.kdnuggets.com/pixi-a-smarter-way-to-manage-python-environments)

[Pixi: pytorch installation](https://pixi.prefix.dev/latest/python/pytorch/#troubleshooting)

