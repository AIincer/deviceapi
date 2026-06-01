# Installieren
```
sudo apt update
sudo apt install openssh-server
sudo systemctl enable ssh
sudo ufw allow ssh
```
test
```
sudo systemctl status ssh
```
name
```
whoami
hostname -I
```
# Key einrichten
user:
```
ssh-keygen
```
- select file -> ""
- Passphrase  -> ""
über ssh verbinden
key einrichten
```
ssh-copy-id <benutzername>@<ip>
```
test: connect -> kein paswort
# Presets einrichten
```
nano ~/.ssh/config
```
presets eingeben
# nutzen
starten
```
ssh <benutzername>@<ip>
```
stoppen
```
exit
```
