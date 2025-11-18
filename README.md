# G3-TiendaOnline

## Descripción del proyecto
G3-TiendaOnline es una tienda creada como parte de nuestro proyecto de FP.

## Estructura del proyecto
TiendaOnline/

├── index.html          # Página de inicio

├── contacto.html       # Página de contacto

├── styles.css          # Estilos de la página

├── images/             # Carpeta con imágenes de productos

└── README.md           # Descripción del proyecto

## Objetivos
* Aplicar los conocimientos de HTML, CSS y Git aprendidos.
* Aprender a trabajar en equipo.

## Integrantes del proyecto
* Integrante 1: Maksim Uncu
* Integrante 2: Paulina Pillajo 
* Integrante 3: Ainhoa Kirstya 
* Integrante 4: Leidy Peñaranda

## Gestión de tareas
El progreso del proyecto se hace mediante un tablero Kanban en Github, llamado "Desarrollo tienda", que tiene las siguientes columnas:
- **To Do**
- **In Progress**
- **Done**

---

## Como contribuir
1. Clona el repositorio:
```bash
git clone https://github.com/muncu-bit/G3-TiendaOnline.git
cd G3-TiendaOnline
```

2. Actualízate a la rama main y crea una nueva rama que soluciona el issue:
```bash
git checkout main
git pull origin main
git checkout -b issue-1-fix     # Donde cambias 1 al número del issue correspondiente
```

3. Añade tus cambios y haz un commit descriptivo:
```bash
git add .
git commit -m "Tu mensaje - closes 1"   # Donde cambias 1 al número del issue correspondiente
```

4. Empuja la rama y abre el pull request:
```bash
git push -u origin issue-1-fix
```

5. Abre el pull request en github.

6. Tras aprobación y verificación borra la rama remota:
```bash
git push origin --delete issue-1-fix    # Donde cambias 1 al número del issue correspondiente
```