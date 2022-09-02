[![Set-up Nginx Docker Container ]](https://flexivue.org)

## ❔ What you need to run the Nginx Docker Container locally?

### Windows Users
- 👉 [Installed Docker Desktop](https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe)
- 👉 [Enabled WSL 2 feature on Windows](https://docs.docker.com/desktop/windows/wsl/)
- 👉 [Download and install the Linux kernel update package](https://docs.microsoft.com/en-us/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package)

---

## ⚙ Installation

### Project setup for Windows Users

- open ubuntu app on windows
- create projects folder at top level
- clone the schnapsterdog/nginx-docker-container repo from github inside projects folder
- pull the image from dockerhub with docker pull schnapsterdog/nginx-docker-container:latest
- get the full path of the nginx-docker-container project -> will need for runing the project
- run the image with docker run --rm -p 80:80 -v /home/yourUbuntuUserName/projects/nginx-docker-container/src:/var/www/html/public schnapsterdog/nginx-docker-container

#### Real time modification

- 👉 Now you will be able to see the page that comes from the project using nginx. Just type localhost inside your browser.
- 👉 You can open another terminal of ubuntu in windows. Navigate to the projects/nginx-docker-container and type code .
- 👉 The project will be openned withing your code editor. If you change something inside src/index.html file, the changes will be applied immediatelly.

## Contact

If you need to learn more about running docker containers, setting up nginx server, please send an e-mail to me via [oliver@akrinum.com](mailto:oliver@akrinum.com).