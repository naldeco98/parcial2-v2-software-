# parcial2-v2-software-
Parcial 2 para materia de ingenieria de software istea

Nicolas Aldeco - 18/11/2026

## Iniciar contenedor docker

## Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/parcial2-v2-software.git
cd parcial2-v2-software
```
---
## Construir la imagen Docker
```bash
docker build -t parcial2-app .
```
---
## Iniciar el contenedor
```bash
docker run -p 8080:80 parcial2-app
```
Abrir en el navegador la instancia local: [http://localhost:8080](http://localhost:8080)