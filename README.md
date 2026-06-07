<!-- BACK TO TOP ANCHOR -->

<a id="readme-top"></a>

<!-- LOGO -->
<div align="center">
  <a href="https://leonardo-vasconcellos.vercel.app/portfolio/adhonep">
    <img src="assets/logo/adhonep.png" alt="Logo" width="80" height="80">
  </a>

  <h1 align="center">ADHONEP Meetup System</h1>

  <p align="center">A browser-based desktop application for managing members, agenda, and resources for the ADHONEP association.</p>

  <p align="center">// association management · adhonep.org.br</p>

  <br />

<a href="https://leonardo-vasconcellos.vercel.app/portfolio/adhonep"><strong>View it live »</strong></a>

</div>

<br />

<!-- SHIELDS -->
<div align="center">

[![Creator Website][website-shield]][website-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Released][year-shield]][year-url]

</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#demo">Demo</a></li>
    <li><a href="#screenshots">Screenshots</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

[![Product Screenshot][product-screenshot]](https://leonardo-vasconcellos.vercel.app/portfolio/adhonep)

<!-- PROJECT INTRO: 260 chars max -->

A desktop-style web application built for the ADHONEP association, providing member management, event scheduling, and access control through a multi-window ExtJS interface backed by a CodeIgniter PHP API.

<!-- END INTRO -->

ADHONEP Meetup System is a browser-based, desktop-style web application built for the ADHONEP association (adhonep.org.br). It provides a centralized platform for managing the association's members, events, and operations.

The system was designed to give office staff a familiar desktop-application experience inside the browser. ExtJS 3.0's component library renders multi-window panels, sortable data grids, and rich form controls — all without page reloads. Every interaction stays within a single-page shell that behaves like a native application.

The backend is a PHP application built on CodeIgniter 2.1.3, exposing a JSON API consumed entirely by the ExtJS frontend. Controllers cover every core domain: member records (Pessoas), cities and locations (Cidades, Locais), scheduled events (Agenda), document downloads, shared ideas, and system-level configuration. A helper-based access control layer enforces login sessions before any protected resource is served.

A strict naming convention was established to keep the large ExtJS codebase organized across modules. Form IDs, grid column IDs, datastore IDs, window IDs, and field translation keys all follow predictable patterns derived from the entity name — for example, `id-form-ins-pessoas`, `id-grid-pessoas`, `id-window-funcao-pessoas`. This made it practical for a small team to maintain and extend a growing number of modules over several years without coordination overhead.

The system was originally deployed in 2009 and remained in active use through 2014.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- DEMO -->

## Demo

<div align="center">
  <a href="https://youtu.be/B9V2zb7emKs">
    <img src="https://img.youtube.com/vi/B9V2zb7emKs/maxresdefault.jpg" alt="Watch the demo" style="border-radius:6px;max-width:100%;" />
  </a>
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SCREENSHOTS -->

## Screenshots

<div align="center" style="display:flex;flex-wrap:wrap;gap:8px;justify-content:center;">
  <a href="screenshots/screencapture-house-devhouse-br-showcase-adhonep-2018-07-20-16_35_54.png"><img src="screenshots/screencapture-house-devhouse-br-showcase-adhonep-2018-07-20-16_35_54.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/screencapture-house-devhouse-br-showcase-adhonep-desktop-html-2018-07-20-16_36_51.png"><img src="screenshots/screencapture-house-devhouse-br-showcase-adhonep-desktop-html-2018-07-20-16_36_51.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/screencapture-house-devhouse-br-showcase-adhonep-desktop-html-2018-07-20-16_37_18.png"><img src="screenshots/screencapture-house-devhouse-br-showcase-adhonep-desktop-html-2018-07-20-16_37_18.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/screencapture-house-devhouse-br-showcase-adhonep-desktop-html-2018-07-20-16_37_38.png"><img src="screenshots/screencapture-house-devhouse-br-showcase-adhonep-desktop-html-2018-07-20-16_37_38.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/screencapture-house-devhouse-br-showcase-adhonep-desktop-html-2018-07-20-16_39_30.png"><img src="screenshots/screencapture-house-devhouse-br-showcase-adhonep-desktop-html-2018-07-20-16_39_30.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
  <a href="screenshots/screencapture-house-devhouse-br-showcase-adhonep-desktop-html-2018-07-20-16_38_33.png"><img src="screenshots/screencapture-house-devhouse-br-showcase-adhonep-desktop-html-2018-07-20-16_38_33.png" height="220" style="object-fit:cover;border-radius:6px;" /></a>
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- BUILT WITH -->

## Built With

**Languages**

|                                                                                                                | Language   | Version |
| -------------------------------------------------------------------------------------------------------------- | ---------- | ------- |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="20" />               | PHP        | 5.x     |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="20" /> | JavaScript | ES5     |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="20" />           | HTML       | 5       |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="20" />             | CSS        | 3       |

**Frameworks & Libraries**

|                                                                                                               | Framework   | Version |
| ------------------------------------------------------------------------------------------------------------- | ----------- | ------- |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/codeigniter/codeigniter-plain.svg" width="20" /> | CodeIgniter | 2.1.3   |
| <img src="https://www.sencha.com/wp-content/uploads/2020/12/ExtJS_logo_svg.svg" height="20">                  | Ext JS      | 3.0.0   |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="20" />          | MySQL       | —       |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- OTHER -->

# Nomenclaturas:

exemplo: Objeto Pessoas

| JAVASCRIPT                       |                                     |
| -------------------------------- | ----------------------------------- |
| Arquivo JS formuário             | FormPessoas.js                      |
| Arquivo JS Grid                  | Grid Pessoas                        |
| Objeto Módulo                    | DevHouseDesktop.ModuloGridPessoas   |
| ID Módulo                        | id-modulo-funcaodomodulo-pessoas    |
| PlaceHolder Para TIP             | id-pessoas-nomedocampo-tip          |
| Traducao Nome de Campos          | Ext.names.PessoasNomeDoCampoField   |
| ID de Coluna de Grid             | id-col-pessoas-nomedocampo          |
| ID de Formulario Insert/Update   | id-form-ins-pessoas                 |
| ID de Formulario Filtro          | id-form-filtro-pessoas              |
| ID de Botão                      | id-btn-funcao-pessoas               |
| ID de Campo de Formulário        | id-field-pessoas-nomedocampo        |
| ID de Campo de Formulário Filtro | id-field-pessoas-search-nomedocampo |
| ID de Grid                       | id-grid-pessoas                     |
| ID de Janela                     | id-window-funcao-pessoas            |
| ID de Painel                     | id-panel-funcao-pessoas             |
| ID DataStore                     | id-datastore-grid-pessoas           |

<!-- ROADMAP -->

## Roadmap

This project repository is for archive purposes only. No new features or issues are being tracked.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTORS -->

## Contributors

<a href="https://github.com/llvasconcellos2/adhonep/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=llvasconcellos2/adhonep" alt="Contributors" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

[Leonardo Vasconcellos](https://leonardo-vasconcellos.vercel.app/) — leonardolimadevasconcellos@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->

[website-shield]: https://img.shields.io/badge/Creator_Website-%E2%86%97-2eba7a?style=for-the-badge
[website-url]: https://leonardo-vasconcellos.vercel.app/
[contributors-shield]: https://img.shields.io/github/contributors/llvasconcellos2/adhonep.svg?style=for-the-badge
[contributors-url]: https://github.com/llvasconcellos2/adhonep/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/llvasconcellos2/adhonep.svg?style=for-the-badge
[forks-url]: https://github.com/llvasconcellos2/adhonep/network/members
[issues-shield]: https://img.shields.io/github/issues/llvasconcellos2/adhonep.svg?style=for-the-badge
[issues-url]: https://github.com/llvasconcellos2/adhonep/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://www.linkedin.com/in/llvasconcellos
[year-shield]: https://img.shields.io/badge/Released-2009-gray?style=for-the-badge
[year-url]: #
[product-screenshot]: screenshots/screencapture-house-devhouse-br-showcase-adhonep-desktop-html-2018-07-20-16_38_33.png
