# 🧱 Ashiba.ninja (足場)

Foundation for efficient PHP (but not only PHP) development with ready-to-use PHP, SSL, custom proxy domains, and docker.

![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![macOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)

---

## ⚙️ Requirements

1. Docker must be installed. [How to install](https://docs.docker.com/desktop/install/mac-install/)
2. mkcert must be installed. [How to install](https://github.com/FiloSottile/mkcert?tab=readme-ov-file#installation)
3. macOS or Linux (*💡 Windows support soon*)

## 🐾 Getting started

1. Clone the repository.
2. Allow `setup.sh` to execute
```
chmod +x setup.sh
```
3. Type `./setup.sh` with 2 arguments (ℹ️ *script will ask for root permissions to modify virtual hosts and refresh DNS*)
```
./setup.sh $DOCKER_PROJCT_NAME $SITE_NAME
```

- `$DOCKER_PROJECT_NAME` - name of Docker container e.g. *ashiba_ninja*
- `$SITE_NAME` - site domain e.g. *ashiba.ninja*

4. ✅ Done, try your new local website on *$SITE_NAME* you passed to the `setup.sh` script. Now you can freely install whatever you need for your development, the sky is the limit ~ Happy coding, Ninja! 🥷

## 👏 Credits

- [dunglas/frankenphp](https://github.com/dunglas/frankenphp)
