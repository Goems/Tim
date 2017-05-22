
### Analyse comparative d'outils de déploiment et de configuration automatisée
TIM Fin de stage
Présenté par Valentin GOEMANNE

Sous la direction de Sébastien DUPONT 

Mai 2017

---
## Remerciment
---
## Sommaire
 - <span class ="fragment">Présentation de la problématique</span>  
 - <span class ="fragment">Présentation des solutions</span>
 - <span class ="fragment">Analyse comparative des solutions </span>

---

### La problématique ?
- <span class="fragment"> L'installation et la configuration de serveurs ou de machines prend du temps </span>

+++

![Image](giphy.gif)

---

### Les solutions

- <span class="fragment">Puppet</span>
- <span class="fragment">Chef</span>
- <span class="fragment">Ansible</span>
- <span class="fragment">Saltstack</span>
- <span class="fragment">OpenShift</span>

+++
### Puppet

- <span class="fragment">Puppet Labs</span>
- <span class="fragment">2003</span>
- <span class="fragment">Ruby</span>
- <span class="fragment">Serveur/Client</span>
- <span class="fragment">Manifest en RubyDSL</span>
- <span class="fragment">Apache 2.0</span>
+++
#### OpenSource vs Entreprise
<table style="font-size: 50%;">
  <tr>
    <th></th>
    <th>OpenSource</th>
    <th>Entreprise</th>
  </tr>
  <tr>
    <td>Interface graphique</td>
    <td>No</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td>Permision des utilisateur</td>
    <td>No</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td>Management des Noeud</td>
    <td>No</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td>prix</td>
    <td>0 euro</td>
    <td>~100 euro pour le standard
    ~150 euro pour le prenium</td>
  </tr>
  <tr>
    <td>OpenShift</td>
    <td>***</td>
  </tr>
  
</table>

+++
### Chef
+++
### Ansible
+++
### SaltStack
+++
### Virtualisation Vs Conteneurs

<span class="fragment">![Image](CaptureDocker1.png)</span>

+++
### OpenShift 

---

### Les critères de comparaison 
- <span class="fragment">Facilité d'installation</span>
- <span class="fragment">Facilité d'utilisation</span>
- <span class="fragment">Scalable</span>
- <span class="fragment">Architecture</span>
- <span class="fragment">Repositerie</span>
- <span class="fragment">Langage</span>
- <span class="fragment">Plateformes supportées</span>

+++
<table style="font-size: 50%;">
  <tr>
    <th>Solutions</th>
    <th>Facilité d'installation</th>
    <th>Facilité d'utilisation</th>
    <th>Scalable</th>
    <th>Archicteture</th>
    <th>Repositeries</th>
    <th>Ecrit en</th>
    <th>Fichier de travail</th>
    <th>Language fichier </th>
  </tr>
  <tr>
    <td>Puppet</td>
    <td>°°°°</td>
    <td>°°°°</td>
    <td>***</td>
    <td>agent</td>
    <td>Forge</td>
    <td>Ruby</td>
    <td>Manifest</td>
    <td>RudyDSL</td>
  </tr>
    <tr>
    <td>Chef</td>
    <td>***</td>
    <td>***</td>
    <td>***</td>
    <td>agent</td>
    <td>Forge</td>
    <td>Ruby</td>
    <td>Manifest</td>
    <td>RudyDSL</td>
  </tr>
    <tr>
    <td>Ansible</td>
    <td>***</td>
    <td>***</td>
    <td>***</td>
    <td>agent</td>
    <td>Forge</td>
    <td>Ruby</td>
    <td>Manifest</td>
    <td>RudyDSL</td>
  </tr>
    <tr>
    <td>SaltStack</td>
    <td>***</td>
    <td>***</td>
    <td>***</td>
    <td>agent</td>
    <td>Forge</td>
    <td>Ruby</td>
    <td>Manifest</td>
    <td>RudyDSL</td>
  </tr>
    <tr>
    <td>OpenShift</td>
    <td>***</td>
    <td>***</td>
    <td>***</td>
    <td>agent</td>
    <td>Forge</td>
    <td>Ruby</td>
    <td>Manifest</td>
    <td>RudyDSL</td>
  </tr>
</table>
+++

---

