# Prestashop hosting playground

This repository contains a environment that allows to test [Prestashop](https://github.com/PrestaShop/PrestaShop) deployment.

This deployment is based on https://github.com/PrestaShop/docker

```sh
$ docker compose up -d prestashop --wait
```

Go to:

- Backend website: <http://127.0.0.1:8080/admin_/>
  - Login: `demo@prestashop.com`
  - Password: `prestashop_demo`

- Frontend: <http://127.0.0.1:8080>
