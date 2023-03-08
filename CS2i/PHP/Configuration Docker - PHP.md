## Solution idéale
- [ ] Debian dans une VM
- [ ] Docker sur la Debian
- [ ] Git sur la Debian, pour vérifier : `git --version` 
- [ ] Configurer Git si nécessaire `git config --global ...` (user.name, user.email)
- [ ] Générer clef ssh sur la Debian
	- `ssh-keygen -t [hash] -C [mail]`
	- Installer la clef SSH sur GitHub
- [ ]  Tester la config : `ssh -T git@github.com`

## VSCode configuration
- [ ] Installer une inteface graphique sur la Debian
```
apt update
apt upgrade
apt install gnome/stable
```

- [ ] Installer VSCode dans la Debian

1. Télecharger le package Debian sur le site de microsoft
2. Installer le package