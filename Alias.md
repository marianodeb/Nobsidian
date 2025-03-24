

### Alias del Sistema 

```bash
# Alias del Sistema
alias buscar='sudo apt search'
alias instalar='sudo apt install'
alias l='ls -l'
alias ld='ls -l --group-directories-first'
alias ll='ls -la'
alias lld='ls -la --group-directories-first'
alias nf='neofetch'
alias e='exit'
alias act='sudo apt update && sudo apt upgrade'
alias eliminar='sudo apt-get --purge remove'

```


```bash
alias cx='cmatrix'
alias hp='htop'
alias n='nvim'
alias c='cd'
alias a='sudo shutdown now'
alias r='sudo reboot'
alias l='lsd -l'
alias i='sudo apt-get install'
alias ll='lsd -la'
alias act='sudo apt-get update && sudo apt-get upgrade'
alias nf='neofetch'
alias mu='cmus'
alias dpkg='sudo dpkg -i'
```


### Alias para MariaDB

```bash
# Alias para MariaDB
alias mariadb_start='sudo systemctl start mariadb'
alias mariadb_stop='sudo systemctl stop mariadb'
alias mariadb_restart='sudo systemctl restart mariadb'
```

### Alias para PostgresSQL

```bash
#Alias para PostgreSQL
alias postgres_start='sudo systemctl start postgresql'
alias postgres_stop='sudo systemctl stop postgresql'
alias postgres_restart='sudo systemctl restart postgresql'
```

### Alias Pihole y Nginx

```bash
#Alias Pihole y Nginx
alias nginx_on='sudo systemctl stop dnsmasq && sudo systemctl start nginx'
alias nginx_off='sudo systemctl stop nginx'
alias pihole_on='sudo systemctl stop nginx && sudo systemctl start dnsmasq'
alias pihole_off='sudo systemctl stop dnsmasq'
```



