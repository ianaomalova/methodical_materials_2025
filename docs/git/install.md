# Установка Git на компьютер

Для того чтобы вы могли работать с системой Git и ее командами, вам необходимо установить ее себе на компьютер. 

Git можно поставить на любую ОС: Windows, macOS и Linux.

### Инструкция для Windows
1. Перейти на официальный сайт: https://git-scm.com/download/win 
2. Установить программу (обычный мастер установки). Оставь все настройки по умолчанию (особенно Git Bash).
3. После установки откройте Git Bash и проверьте:

```bash
git --version
```

Должно вывести что-то вроде:

```bash
git version 2.45.2.windows.1
```

### Инструкция для macOS

1. Самый простой способ — установить через Homebrew (если он есть):
```basg
brew install git
```

2. Либо если нет brew, можете также скачать с официального сайта: https://git-scm.com/download/mac

3. Проверьте установку:
```bash
git --version
```

### Инструкция для Linux 

```basg
sudo apt update
sudo apt install git
git --version
```

Для Fedora / CentOS:
```bash
sudo dnf install git
```

### Первичная обязательная настройка
После установки нужно указать своё имя и email — они будут отображаться в каждом коммите:

```bash
git config --global user.name "Ваше Имя"
git config --global user.email "you@example.com"
```

Проверить:
```bash
git config --list
```

