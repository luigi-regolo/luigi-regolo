<div align="center">

<sub><strong>HOME ASSISTANT / OPEN SOURCE</strong></sub>

# Themes · Dashboards · Automations

Progetti open source dedicati a Home Assistant

Temi, dashboard e automazioni per la casa connessa

<p>
  <a href="#edera"><kbd>Edera</kbd></a>&nbsp;
  <a href="#riscaldamento-intelligente"><kbd>Riscaldamento</kbd></a>&nbsp;
  <a href="#home-mobile"><kbd>Home Mobile</kbd></a>&nbsp;
  <a href="#altre-automazioni"><kbd>Automazioni</kbd></a>
</p>

</div>

---

<div align="center">

<sub><strong>01 / FEATURED PROJECT</strong></sub>

## Edera

**Apri Home Assistant. Il resto può aspettare.**

Un tema per Home Assistant con due modalità coordinate

**Light + Graphite Dark**

</div>

<table>
  <tr>
    <th align="center" width="50%">GRAPHITE DARK</th>
    <th align="center" width="50%">EDERA LIGHT</th>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/luigi-regolo/Edera">
        <img src="https://raw.githubusercontent.com/luigi-regolo/Edera/main/images/edera-mobile-dark.png" alt="Anteprima Edera Graphite Dark su smartphone" height="320">
      </a>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/luigi-regolo/Edera">
        <img src="https://raw.githubusercontent.com/luigi-regolo/Edera/main/images/edera-mobile-light.png" alt="Anteprima Edera Light su smartphone" height="320">
      </a>
    </td>
  </tr>
</table>

<div align="center">

<a href="https://github.com/luigi-regolo/Edera"><strong>Scopri Edera →</strong></a>
&nbsp;&nbsp;·&nbsp;&nbsp;
<a href="https://my.home-assistant.io/redirect/hacs_repository/?owner=luigi-regolo&amp;repository=Edera&amp;category=theme"><strong>Apri in Home Assistant ↗</strong></a>

</div>

---

<div align="center">

<sub><strong>02 / SMART AUTOMATIONS</strong></sub>

## Riscaldamento intelligente

Gestione dei termostati in base alla presenza in casa, con automazioni dedicate ai **giorni feriali** e al **weekend**

</div>

<table>
  <tr>
    <th width="50%" align="center">Lun — Ven</th>
    <th width="50%" align="center">Sab — Dom</th>
  </tr>
  <tr>
    <td valign="top">
      <strong>Uscita da casa</strong>
      <p>Imposta il preset configurato dopo 5 minuti di assenza</p>
      <p><a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fluigi-regolo%2Fautomazioni-home-assistant%2Fblob%2Fmain%2Fautomations%2Friscaldamento%2Friduci_riscaldamento_assenza_feriali.yaml"><strong>Importa blueprint →</strong></a></p>
      <hr>
      <strong>Rientro a casa</strong>
      <p>Imposta il preset configurato dopo 15 secondi di presenza</p>
      <p><a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fluigi-regolo%2Fautomazioni-home-assistant%2Fblob%2Fmain%2Fautomations%2Friscaldamento%2Fripristina_riscaldamento_rientro_feriali.yaml"><strong>Importa blueprint →</strong></a></p>
    </td>
    <td valign="top">
      <strong>Uscita da casa</strong>
      <p>Imposta il preset configurato dopo 2 minuti di assenza</p>
      <p><a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fluigi-regolo%2Fautomazioni-home-assistant%2Fblob%2Fmain%2Fautomations%2Friscaldamento%2Friduci_riscaldamento_assenza_weekend.yaml"><strong>Importa blueprint →</strong></a></p>
      <hr>
      <strong>Rientro a casa</strong>
      <p>Imposta il preset configurato dopo 5 minuti di presenza</p>
      <p><a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fluigi-regolo%2Fautomazioni-home-assistant%2Fblob%2Fmain%2Fautomations%2Friscaldamento%2Fripristina_riscaldamento_rientro_weekend.yaml"><strong>Importa blueprint →</strong></a></p>
    </td>
  </tr>
</table>

<div align="center">

**Anche per le finestre**

<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fluigi-regolo%2Fautomazioni-home-assistant%2Fblob%2Fmain%2Fautomations%2Friscaldamento%2Friduzione_riscaldamento_finestra_aperta.yaml">Apertura →</a>
&nbsp;·&nbsp;
<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fluigi-regolo%2Fautomazioni-home-assistant%2Fblob%2Fmain%2Fautomations%2Friscaldamento%2Fripristino_riscaldamento_finestra_chiusa.yaml">Chiusura →</a>

<p><a href="https://github.com/luigi-regolo/automazioni-home-assistant"><strong>Esplora le automazioni →</strong></a></p>

</div>

<sub>Ogni blueprint deve essere importato, configurato e attivato in Home Assistant. Sono necessari entità di presenza o sensori finestra e termostati con preset compatibili. Le automazioni di rientro impostano il preset scelto, senza recuperare lo stato precedente. Il rilevamento della presenza può essere impreciso.</sub>

---

<sub><strong>03 / MOBILE EXPERIENCE</strong></sub>

<table>
  <tr>
    <td width="57%" valign="middle">
      <h2>Home Mobile</h2>
      <p>Dashboard per smartphone con tema Edera, piantina 3D, ambienti, luci e sicurezza</p>
      <p><a href="https://luigi-regolo.github.io/home-mobile-home-assistant/"><strong>Prova la Live Demo ↗</strong></a></p>
      <p><a href="https://github.com/luigi-regolo/home-mobile-home-assistant"><strong>Esplora il repository →</strong></a></p>
    </td>
    <td width="43%" align="center">
      <a href="https://luigi-regolo.github.io/home-mobile-home-assistant/">
        <img src="https://raw.githubusercontent.com/luigi-regolo/home-mobile-home-assistant/main/screenshots/home-mobile-original-top.jpg" alt="Anteprima della dashboard Home Mobile" height="245">
      </a>
    </td>
  </tr>
</table>

---

<sub><strong>04 / EXPLORE MORE</strong></sub>

## Altre automazioni

Blueprint per Home Assistant da importare e configurare

<kbd>Sicurezza</kbd>&nbsp; <kbd>Sensori</kbd>&nbsp; <kbd>Tapparelle</kbd>&nbsp; <kbd>NFC</kbd>&nbsp; <kbd>Ingresso</kbd>&nbsp; <kbd>Prese</kbd>

**[Esplora la raccolta completa →](https://github.com/luigi-regolo/automazioni-home-assistant)**

---

<div align="center">

<sub>OPEN SOURCE PROJECTS · HOME ASSISTANT</sub>

</div>
