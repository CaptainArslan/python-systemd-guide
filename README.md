# Deploy Python on Ubuntu

A copy-paste, step-by-step guide for deploying a Python application on Ubuntu using a virtual environment and systemd. Covers installing dependencies, writing the systemd service file, setting permissions, enabling the service, checking logs with journalctl, and routine redeployment. Includes dark and light mode.

**[View the live guide →](https://CaptainArslan.github.io/deploy-python-ubuntu/)**

## What's covered

1. Installing Python and required packages
2. Setting up the project directory and virtual environment
3. Testing the application manually
4. Writing the systemd unit file
5. Setting correct file/folder permissions
6. Enabling and starting the service
7. Verifying status and reading logs with `journalctl`
8. A `systemctl` command cheatsheet
9. Keeping `venv/` out of Git with `.gitignore`
10. Routine redeployment after a `git pull`
11. A complete, copy-all initial setup script
12. A directory structure and boot-sequence map

## Using this guide

Every command block has a **Copy** button — no manual selecting and pasting. Wherever you see `myapp` or `/var/www/myapp`, swap in your own application name and path.

Toggle **dark / light mode** with the button in the top-right corner; your preference is remembered on your next visit.

## Running it locally

This is a single self-contained HTML file — no build step, no dependencies.

```bash
git clone https://github.com/CaptainArslan/deploy-python-ubuntu.git
cd deploy-python-ubuntu
open index.html   # or just double-click it in Finder/Explorer
```

## Hosting

This repo is set up for [GitHub Pages](https://pages.github.com/), served from the `main` branch, root folder.

## License

Free to use, copy, and adapt for your own deployment docs.