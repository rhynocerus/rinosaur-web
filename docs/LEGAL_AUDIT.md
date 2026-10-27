# Auditoría documental y de licencias — Rinosaur Web

**Estado:** revisión inicial; sin licencia nueva aprobada.
**Repositorio:** https://github.com/rhynocerus/rinosaur-web

## Función actual

Este repositorio mantiene redirecciones hacia la versión oficial de Rinosaur:
https://rinosaur-rhynus.rhynus.chatgpt.site/

La rama `main` examinada contiene `README.md`, páginas HTML de redirección en la raíz y en `2d/`, `3d/` y `webxr/`, además de un flujo de despliegue de GitHub Pages. No se ha identificado un archivo `LICENSE` en el árbol revisado.

## Procedencia y licencias

- GitHub no identifica el repositorio como fork.
- Los HTML de redirección y la documentación deben considerarse separadamente del código, arte, sonido y modelos del juego alojado en el Site oficial.
- La ausencia de `LICENSE` no concede automáticamente permiso para reproducir o relicenciar estos archivos.
- El flujo de GitHub Actions usa `actions/checkout@v4`, `actions/configure-pages@v5`, `actions/upload-pages-artifact@v3` y `actions/deploy-pages@v4`. Son herramientas de despliegue externas; conviene conservar el registro de las versiones utilizadas y evaluar sus condiciones cuando sea necesario.

## Política provisional

No incorporar una licencia al repositorio ni extenderle automáticamente la licencia futura del juego. Primero definir la titularidad del código de redirección y su relación con el proyecto Rinosaur. Mantener intactas las rutas, el destino oficial y el despliegue.

## Próximos pasos

1. Determinar los permisos que RIW desea conceder respecto al código propio de redirección.
2. Comprobar las atribuciones y avisos necesarios de los componentes de despliegue.
3. Coordinar la decisión documental con la auditoría aún abierta en `rhynocerus/rinosaur`, PR #7.
4. Preparar cambios separados si resultan necesarios, tras aprobación expresa.

**Conclusión:** no hay evidencia que obligue a cambiar ahora el funcionamiento del repositorio. Auditoría documental preliminar; decisión de licencia pendiente.
