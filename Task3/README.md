

## 1. Устанавливаем OpenSSH - 
в PowerShell запускаем команжду:  Get-WindowsCapability -Online | Where-Object Name -like ‘OpenSSH.Server*’ | Add-WindowsCapability –Online
![Image](/Task3/img/ssh_win.png)

## 2. Разрешить подключение по RDP
1. Переходим в "Удаленный рабочий стол" - ""Включить удаленный рабочий стол" - "Включено"
2. в PowerShell запускаем команжду : New-NetFirewallRule -Name "RDP" -DisplayName "Remote Desktop" -Enabled True -Direction Inbound -Protocol TCP -Action Allow -LocalPort 3389
![Image](/Task3/img/rdp.png)

## 3. Провести сканирование подсети с ВМ Kali
![Image](/Task3/img/nmap.png)

## 4. Провести BruteForce (ssh) пароля от ВМ Win10

1. Установка Hydra: 
```bash
sudo apt update
sudo apt install hydra
```

2. Создаем файл со списком возможных паролей.
![Image](/Task3/img/pswd.png)

3. Проводим поиск комбинации логин/пароль 
![Image](/Task3/img/hydra.png)