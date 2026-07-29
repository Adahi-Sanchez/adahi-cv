<style>
  @page {
    size: A4;
    margin: 8.5mm 11mm;
  }
  body {
    font-family: 'Segoe UI', Arial, sans-serif;
    font-size: 8.8pt;
    line-height: 1.3;
    color: #1e293b;
  }
  .header-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 2px solid #0284c7;
    padding-bottom: 6px;
    margin-bottom: 6px;
  }
  .header-text {
    flex: 1;
  }
  .header-photo {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    object-fit: cover;
    object-position: center top;
    margin-left: 14px;
    border: 2px solid #0284c7;
  }
  h1 {
    font-size: 16pt;
    color: #0f172a;
    margin: 0 0 2px 0;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }
  .contact-info {
    font-size: 8.3pt;
    color: #475569;
  }
  h2 {
    font-size: 9.5pt;
    color: #0284c7;
    border-bottom: 1px solid #cbd5e1;
    margin: 8px 0 4px 0;
    padding-bottom: 2px;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }
  .item-title {
    font-size: 8.8pt;
    font-weight: bold;
    color: #0f172a;
    margin-top: 4px;
    margin-bottom: 1px;
  }
  .item-sub {
    font-size: 8.2pt;
    color: #0284c7;
    font-weight: 600;
  }
  ul {
    margin: 2px 0 4px 0;
    padding-left: 14px;
  }
  li {
    margin-bottom: 2px;
  }
  a {
    color: #0284c7;
    text-decoration: none;
  }
</style>

<div class="header-container">
  <div class="header-text">
    <h1>ADAHI SÁNCHEZ GÓMEZ</h1>
    <div class="contact-info">
      <b>Técnico de Sistemas, Redes e Infraestructura TI | Ciberseguridad & Cloud</b><br>
      Cáceres y alrededores | Teletrabajo | (+34) 653 51 42 65 | adahisanchez5@gmail.com | Carné B (Vehículo propio)<br>
      <a href="https://www.linkedin.com/in/adahi-sanchez-gomez">LinkedIn: adahi-sanchez-gomez</a> | <a href="https://github.com/Adahi-Sanchez">GitHub: Adahi-Sanchez</a>
    </div>
  </div>
  <img class="header-photo" src="foto.png" alt="Foto Adahi">
</div>

## PERFIL PROFESIONAL
Técnico Superior ASIR especializado en arquitectura Zero Trust, administración de servidores (Linux/Windows Server), virtualización en Proxmox VE y automatización con PowerShell. Experiencia en soporte N1/N2, resolución de incidencias complejas (Troubleshooting) y trabajo bajo presión en entorno multinivel.

## HABILIDADES TÉCNICAS
* **Sistemas y Virtualización:** Windows Server 2022, Linux (Ubuntu/Debian), Proxmox VE, Active Directory (AD DS, GPO, DNS, DHCP, WSUS).
* **Redes y Ciberseguridad:** Modelo Zero Trust, Tailscale (VPN Mesh), SIEM (Wazuh), NIDS/IPS (Suricata, CrowdSec), Hardening, MFA.
* **Contenedores y Scripting:** Docker, Docker Compose, PowerShell, Bash, Batch, Python, Tesseract OCR.
* **Bases de Datos y Web:** SQL Server 2022, PostgreSQL, MySQL, SQLite, C# (ASP.NET), HTML5/CSS3.

## EXPERIENCIA PROFESIONAL

<div class="item-title">Técnico de Sistemas e Infraestructura TI <span style="float:right; font-weight:normal;">Ene. 2026 – Abr. 2026</span></div>
<div class="item-sub">Escuela Politécnica de Cáceres - Universidad de Extremadura</div>
<ul>
  <li>Mantenimiento de infraestructura TI, virtualización con Proxmox VE/VirtualBox y administración de usuarios en Active Directory.</li>
  <li>Despliegue de cableado LAN, cobertura Wi-Fi corporativa, montaje físico de servidores y reparación avanzada de electrónica/hardware.</li>
  <li>Redacción de documentación arquitectónica y guías de despliegue para aplicaciones web (Python, Django, Nginx, PostgreSQL).</li>
</ul>

<div class="item-title">Técnico de Soporte Informático y Redes <span style="float:right; font-weight:normal;">Mar. 2024 – Jun. 2024</span></div>
<div class="item-sub">Ayuntamiento de Plasencia</div>
<ul>
  <li>Soporte N1/N2 a usuarios multisede y clonación masiva de imágenes de SO (Windows/Linux) mediante unidades USB en cascada.</li>
  <li><b>Logro destacado:</b> Diagnóstico y solución definitiva a un fallo de conectividad remota en la Policía Local, restableciendo el acceso seguro.</li>
  <li>Crimpado y certificación de red LAN, configuración IP en routers/switches y gestión de permisos en Active Directory.</li>
</ul>

<div class="item-title">Personal de Tienda / Logística y Operaciones <span style="float:right; font-weight:normal;">Campañas de Verano (2024, 2025, 2026)</span></div>
<div class="item-sub">Mercadona / Spar Express</div>
<ul>
  <li><b>Reincorporación recurrente en Mercadona:</b> Selección consecutiva en campañas estivales superando sus altos estándares de calidad y exigencia procedimental, demostrando fiabilidad.</li>
  <li>Gestión logística de almacén, control informatizado de inventario (PDA/radiofrecuencia) y trazabilidad bajo sistema FIFO.</li>
  <li>Operativa de caja (TPV), atención al público y resolución de incidencias en entornos de alto volumen bajo estricta presión de tiempos.</li>
</ul>

## PROYECTOS DESTACADOS
* **Smart NAS & AI Engine (Docker):** Servidor de archivos en Docker Compose con motor OCR en Python para clasificación automática de documentos en tiempo real. [<a href="https://github.com/Adahi-Sanchez/Smart-NAS-AI-Docker">GitHub</a>]
* **PIONERO-S01 (Arquitectura Zero Trust & SOC):** Infraestructura corporativa en Proxmox VE, Windows Server 2022 y VPN Mesh con stack SOC defensivo (Wazuh SIEM, Suricata, CrowdSec) y portal C#. [<a href="https://github.com/Adahi-Sanchez/PIONERO-S01-Infraestructura-y-Gestion-Web">GitHub</a>]
* **Active Directory Automated Provisioning:** Suite de 16 scripts en PowerShell para la automatización y aprovisionamiento masivo de +200 objetos en AD DS con permisos NTFS/SMB. [<a href="https://github.com/Adahi-Sanchez/AD-Automated-Deployment-PowerShell">GitHub</a>]
* **Diauto E-Commerce:** Plataforma web multimarca desarrollada en sprint de 72h con HTML5, CSS Flexbox y Python. [<a href="https://github.com/Adahi-Sanchez/Diauto-Concesionario-Web">GitHub</a>]

## FORMACIÓN ACADÉMICA
* **Curso de Especialización en Ciberseguridad en Entornos TI (Máster FP)** | IES Valle del Jerte — ***Cursando actualmente (2026–2027)***
* **C.F.G.S. Administración de Sistemas Informáticos en Red (ASIR)** | IES Ágora *(2024–2026)* — **Expediente de Excelencia Académica**
* **C.F.G.M. Sistemas Microinformáticos y Redes (SMR)** | IES Valle del Jerte *(2022–2024)*

## CERTIFICACIONES Y DATOS DE INTERÉS
* **Certificaciones:** Cloud Azure AZ-104 (OpenWebinars), Admin Linux & PowerShell (OpenWebinars), SQL/MySQL/MongoDB (OpenWebinars), Gestión de Proyectos Ágiles Scrum (UEX 1 ECTS), Prevención de Riesgos Laborales (PRL).
* **Idiomas y Movilidad:** Español (Nativo), Inglés (Técnico / Lectura fluida B1-B2). Disponibilidad para Cáceres y alrededores, o Teletrabajo.