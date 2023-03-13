# PRACTICA
## Esto es una practica del uso de Mark Down para generar texto

### El ejercicio consiste en crear una tabla con 2X2  con los 5 comandos que se junto con su descripcion

| COMANDO | DESCRIPCION |
|--------|-------------|
| ls | Listar todos los archivos |
| pwd | Direccion en la que me encuentro |
| cd | Cambiar de directorio |
| rm | Remover un archivo o directorio |
| cp | Copiar un archivo o directorio |

### El otro ejercicio consiste en escribir un alias para listar el top 10 comandos mas usados
```
alias mostused='history' | awk '\''{print $2}'\''| sort | uniq -c | sort -nr | head -n 10'
```

### Esto es un cambio para probar git merge