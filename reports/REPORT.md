# Лабораторная работа №16. Отчет.

## Задание на лабораторную работу:

- [x] 1. Ознакомиться со ссылками учебного материала
- [x] 2. Выполнить инструкцию учебного материала
- [x] 3. Составить отчет и отправить ссылку личным сообщением в **Slack**

## Выполнение работы.
	
В соответствии с последовательностью, определенной заданием на лабораторную работу, были выполнены следующие действия:
- [X] Для успешного выполнения задания создан новый пустой репозиторий lab16 с лицензией MIT.
- [X] 1. Проведено ознакомление по приведенным ссылкам со следующими материалами по [Tmux](https://tmux.github.io).
- [X] 2. Выполнена следующая последовательность команд:

## Tutorial

```ShellSession
$ export GITHUB_USERNAME=woz91
```

```ShellSession
$ git clone https://github.com/${GITHUB_USERNAME}/lab14 lab16
$ cd lab14
$ git remote remove origin
$ git remote add origin git@github.com:${GITHUB_USERNAME}/lab16
```

## Tutorial

```ShellSession
$ tmux
$ tmux new -s vaulex
```

```ShellSession
$ tmux a
$ tmux a -t vaulex
```

```ShellSession
$ tmux ls
$ tmux kill-session -t vaulex
```

```ShellSession
<C-B>s
<C-B>$
```

```ShellSession
<C-B>c
<C-B>w
<C-B>n
<C-B>p
<C-B>f
<C-B>,
<C-B>&
```

```ShellSession
<C-B>%
<C-B>"
<C-B>o
<C-B>q
<C-B>x
<C-B>+
<C-B>-
<C-B>⍽
```

## Report

```ShellSession
$ cd ~/workspace/labs/
$ export LAB_NUMBER=16
$ git clone https://github.com/tp-labs/lab${LAB_NUMBER} tasks/lab${LAB_NUMBER}
$ mkdir reports/lab${LAB_NUMBER}
$ cp tasks/lab${LAB_NUMBER}/README.md reports/lab${LAB_NUMBER}/REPORT.md
$ cd reports/lab${LAB_NUMBER}
$ edit REPORT.md
$ gistup -m "lab${LAB_NUMBER}"
```

- [X] 4. Составлен отчет о работе в формате MD, ссылка отправлена в **slack**.

	
>## Выводы:

>В ходе проделанной работы проведено ознакомление с менеджером терминалов **Tmux**, создана и окончена терминальная сессия, изучены управляющие сочетания клавиш.
