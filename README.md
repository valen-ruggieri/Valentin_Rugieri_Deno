# Valentin_Rugieri_Deno 🦕 📦 ✨

[![Deno CI](https://github.com/MichaelCurrin/deno-project-template/workflows/Deno%20CI/badge.svg)](https://github.com/MichaelCurrin/deno-project-template/actions?query=workflow:"Deno+CI" "GitHub Actions CI")
[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/deno-project-template?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/deno-project-template/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Deno](https://img.shields.io/badge/Deno-1.x-blue?logo=deno&logoColor=white)](https://deno.land)


<div align="center">
    <a href="https://deno.land" title="Go to Deno homepage">
        <img src="https://raw.githubusercontent.com/github/explore/master/topics/deno/deno.png"
             alt="node icon"
             width="130" height="130" />
    </a>
</div>


## Sample usage

Iniciar servidor usando el siguiente comando

```console
$ deno run --allow-net --watch server.tsx

```
## Tasks

### Create server in deno

Crear un servidor que utilice el módulo http servest y genere la vista con React render.

### Config server and create react view

- Configurar denon para que, ante un cambio de código, el servidor de reinicie automáticamente.
- El servidor presentará en su ruta raíz un formulario de ingreso de un color, que será enviado al mismo por método post. Dicho color (en inglés) será incorporado a un array de colores persistido en memoria.
- Por debajo del formulario se deberán representar los colores recibidos en una lista desordenada (ul) utilizando el mismo color para la letra en cada caso. El color de fondo del la vista será negro.
