# NUXT_JS_GERLESSVER

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/edinaldorodriguesceara/nuxt_js_gerlessver/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/edinaldorodriguesceara/nuxt_js_gerlessver/tree/master)

<p align="center">
  <img src="https://nuxt.com/assets/design-kit/icon-green.svg" alt="Nuxt.js Logo" width="150"/>
</p>

https://github.com/juniormesquitadandao/gerlessver

```bash
git clone https://github.com/edinaldorodriguesceara/nuxt_js_gerlessver
cd nuxt_js_gerlessver
  
  ARG_USER_UID=$(id -u) ARG_USER_GID=$(id -g) docker compose config
  ARG_USER_UID=$(id -u) ARG_USER_GID=$(id -g) docker compose build
  docker compose up -d
  docker compose exec app bash
    cat /etc/hosts | grep dockerhost

    npm install
    npm run test
    npm run dev
    # Brower: http://localhost:3000
    # Press: CTRL+C
    git status
    git add .
    git commit -m 'update'
    git push
    exit
  docker compose down
