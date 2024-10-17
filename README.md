
# GIT
## Convertir tu proyecto en un proyecto controlado por **git**
```
git init
```

## Configurar git *correctamente*
```
git config --global user.email "xxx@gmail.com"
git config --global user.name "xxx"
```

## Prepara los cambios para ser anadidos al repositorio
```
git add xxx (archivo que quiero anadir) OR . (todo)
```

## Guarda los cambios en el repositorio
```
git commit -m "creo la pagina web inicial"
```

## Conecta el repositorio local con el repositorio remoto
```
git remote add origin https://github.com/IsmaelA852/webprueba.git
```

## Sube los cambios que tienes en local a el repositorio remoto
```
git push -u origin master
```