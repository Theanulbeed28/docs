---
title: Visualizar una solicitud de extracción en GitHub Desktop
shortTitle: Visualizar una solicitud de extracción
intro: 'Puedes ver los cambios propuestos en las solicitudes de extracción abiertas en {% data variables.product.prodname_desktop %}.'
redirect_from:
  - /desktop/contributing-to-projects/accessing-a-pull-request-locally
  - /desktop/contributing-and-collaborating-using-github-desktop/accessing-a-pull-request-locally
  - /desktop/contributing-and-collaborating-using-github-desktop/viewing-a-pull-request-in-github-desktop
versions:
  fpt: '*'
---

## Acerca de las solicitudes de extracción en {% data variables.product.prodname_desktop %}
Puedes ver las solicitudes de extracción que tú o tus colaboradores hayan propuesto en {% data variables.product.prodname_desktop %}. Las solicitude de extracción te permiten proponer cambios a los proyectos, proporcionar retroalimentación y revisiones, y fusionar cambios en los proyectos. Para obtener más información, consulta "[Acerca de las solicitudes de extracción](/github/collaborating-with-issues-and-pull-requests/about-pull-requests)."

Cuando visualizas una solicitud de extracción en {% data variables.product.prodname_desktop %}, puedes ver un historial de confirmaciones que han hecho los colaboradores. También puedes ver qué archivos modificaron, agregaron o borraron estas confirmaciones. Desde {% data variables.product.prodname_desktop %}, puedes abrir los repositorios en tu editor de texto preferido para ver cualquier cambio o para hacer cambios adicionales. Después de recibir los cambios en una solicitud de extracción, puedes dar retroalimentación en {% data variables.product.prodname_dotcom %}. Para obtener más información, consulta la sección "[Acerca de las revisiones de las solicitudes de extracción](/github/collaborating-with-issues-and-pull-requests/about-pull-request-reviews)".

Si se habilitaron las verificaciones en tu repositorio, {% data variables.product.prodname_desktop %} mostrará el estado de ellas en la solicitud de cambios y te permitirá volver a ejecutarlas. For more information, see "[Viewing and re-running checks in GitHub Desktop](/desktop/contributing-and-collaborating-using-github-desktop/working-with-your-remote-repository-on-github-or-github-enterprise/viewing-and-re-running-checks-in-github-desktop)."

## Visualizar una solicitud de extracción en {% data variables.product.prodname_desktop %}
{% data reusables.desktop.current-branch-menu %}
{% data reusables.desktop.click-pull-requests %}
  ![Pestaña Pull Requests en el menú desplegable de la rama actual](/assets/images/help/desktop/branch-drop-down-pull-request-tab.png)
{% data reusables.desktop.choose-pr-from-list %}
  ![Lista de las solicitudes de extracción abiertas en el repositorio](/assets/images/help/desktop/click-pull-request.png)
4. Opcionalmente, para actualizar la lista de solicitudes de extracción, haz clic en {% octicon "sync" aria-label="The sync icon" %}. ![Botón Sync (Sincronizar) para actualizar](/assets/images/help/desktop/pull-request-list-sync.png)

## Abrir una solicitud de extracción en {% data variables.product.prodname_desktop %} desde {% data variables.product.prodname_dotcom %}
{% data reusables.repositories.sidebar-pr %}
2. En la lista de solicitudes de extracción, da clic en la solicitud de extracción que te gustaría abrir en {% data variables.product.prodname_desktop %}.
3. A la derecha del título de la solicitud de extracción, da clic en el menú desplegable de **Abrir con** y después da clic en el botón de **Abrir en Desktop**. ![El botón de Abrir en Desktop](/assets/images/help/desktop/open-pr-in-desktop-button.png)
