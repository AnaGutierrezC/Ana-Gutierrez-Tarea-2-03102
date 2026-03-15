# Ana-Gutierrez-Tarea-2-03102
Configuración del workflow:
1. Se crea el respositorio web llamado Ana-Gutierrez-Tarea-2-03102
2. Se suben los archivos desde los comandos en Visual Studio Code
3. Desde GitHub Actions se crea el main.YML, que, al hacer push se crea dentro de una carpeta llamada .github/workflows
4. El workflow se aconfigura para que se ejecute cada vez que se haga un push a la rama main. usando deploy con ubuntu.
5. Lo que hará es desplegarse el sitio en GitHub Pages, se actualizará manualmente con cada cambio dentro del proyecto a la rama main.
6. Se activó GitHub Pages para poder visualizar el sitio web. 

Cómo resuelve la automatización? 
Se evita que se publique manualmente el sitio web después de cada cambio, además que las actualizaciones del sitio serán más rápidas entre versiones y cada modificación del código se integra rápidamente en el sitio web.
