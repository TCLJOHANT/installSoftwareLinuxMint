# Instalar node js (nvm administraor de node)

```
sudo apt install curl
```

```

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
```

```
source ~/.bashrc
```

```
nvm list-remote
```

> [!NOTE]  
> nvm install numero de version  y las que desees por ejemplo  nvm install 18.19.0



```
nvm install 20.10.0
```

### para ver versiones instaladas en mi equipo usar

```
 nvm list
```
### para cambiar de version usar

> [!NOTE]  
> → para establecer por default


```
 nvm alias default 18.19.0  
```

> [!NOTE]  
> → para usar en ese preciso momento


```
 nvm use v20.10.0  
```