# Pelican Installer

### Какая Операционая система нужна
| Operating System | Version | Supported          | PHP Version |
| ---------------- | ------- | ------------------ | ----------- |
| Ubuntu           | 16.04   | :red_circle:       |             |
|                  | 18.04   | :red_circle: \*    |             |
|                  | 20.04   | :white_check_mark: | 8.3         |
|                  | 22.04   | :white_check_mark: | 8.3         |
|                  | 24.04   | :white_check_mark: | 8.3         |
| Debian           | 8       | :red_circle: \*    |             |
|                  | 9       | :red_circle: \*    |             |
|                  | 10      | :white_check_mark: | 8.3         |
|                  | 11      | :white_check_mark: | 8.3         |
|                  | 12      | :white_check_mark: | 8.3         |
| CentOS           | 6       | :red_circle:       |             |
|                  | 7       | :red_circle: \*    |             |
|                  | 8       | :red_circle: \*    |             |
| Rocky Linux      | 8       | :white_check_mark: | 8.3         |
|                  | 9       | :white_check_mark: | 8.3         |
| AlmaLinux        | 8       | :white_check_mark: | 8.3         |
|                  | 9       | :white_check_mark: | 8.3         |

### Скрипт Установки
```bash
bash <(curl -Ss https://raw.githubusercontent.com/pelican-installer/pelican-installer/Production/install.sh || wget -O - https://raw.githubusercontent.com/pelican-installer/pelican-installer/Production/install.sh) auto
```

### Wings Команды


```bash
systemctl enable --now wings
```

```bash
systemctl restart wings
```
```bash
systemctl start wings
```

