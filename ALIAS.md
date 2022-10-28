# Crear alias para unificar comandos
## *Crear un nuevo alias*
#### por ejemplo el .s se configura como alias de status --short
```
git config --global alias.s "status --short"
```
#### otro ejemplo:
```
git config --global alias.l "log --online --decorate --all --graph"
```

---
#### git log con estilos
```
git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"
```

