
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
- <span class="fragment">SSL</span>
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
    <td>Permision des utilisateurs</td>
    <td>No</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td>Prix</td>
    <td>0 euro</td>
    <td>~100 euro standard
    ~150 euro prenium</td>
  </tr>
</table>

+++
### Chef
- <span class="fragment">Opscode</span>
- <span class="fragment">2009</span>
- <span class="fragment">Ruby</span>
- <span class="fragment">Serveur/Client</span>
- <span class="fragment">SSH</span>
- <span class="fragment">Recipes en RubyDSL</span>
- <span class="fragment">Apache 2.0</span>
+++
### Chef
![Image](chef_repr.png)

+++
### Ansible
- <span class="fragment">Ansible/Red Hat</span>
- <span class="fragment">2012</span>
- <span class="fragment">Python</span>
- <span class="fragment">Client</span>
- <span class="fragment">SSH</span>
- <span class="fragment">Playbook en YAML</span>
- <span class="fragment">GNU</span>
+++
### Ansible Tower
![Image](tower-screenshot-blog2.png)
+++
### SaltStack
- <span class="fragment">Tom Hatch</span>
- <span class="fragment">2011</span>
- <span class="fragment">Python</span>
- <span class="fragment">Serveur/Client</span>
- <span class="fragment">State en YAML </span>
- <span class="fragment">Apache 2.0</span>
+++
### Virtualisation Vs Conteneurs

![Image](CaptureDocker1.png)

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
    <th>Licence</th>
    <th>Repositeries</th>
    <th>Ecrit en</th>
    <th>Fichier de travail</th>
    <th>Language fichier </th>
  </tr>
  <tr>
    <td>Puppet</td>
    <td>°°</td>
    <td>°°°</td>
    <td>°°°</td>
    <td>Serveur/Client</td>
    <td>Apache 2.0</td>
    <td>Forge</td>
    <td>Ruby</td>
    <td>Manifest</td>
    <td>RudyDSL</td>
  </tr>
    <tr>
    <td>Chef</td>
    <td>°°°</td>
    <td>°°°</td>
    <td>°°°</td>
    <td>Serveur/Client</td>
    <td>Apache 2.0</td>
    <td>Supermarket</td>
    <td>Ruby, Erlang</td>
    <td>Recipe</td>
    <td>RudyDSL</td>
  </tr>
    <tr>
    <td>Ansible</td>
    <td>°°°°</td>
    <td>°°°</td>
    <td>°°°</td>
    <td>Client</td>
    <td>GNU</td>
    <td>Galaxy</td>
    <td>Python, PowerShell</td>
    <td>Playbook</td>
    <td>RudyDSL</td>
  </tr>
    <tr>
    <td>SaltStack</td>
    <td>°°°</td>
    <td>°°°</td>
    <td>°°°</td>
    <td>Serveur/Client</td>
    <td>Apache 2.0</td>
    <td>Project</td>
    <td>Python</td>
    <td>State</td>
    <td>YAML</td>
  </tr>
    <tr>
    <td>OpenShift</td>
    <td>***</td>
    <td>***</td>
    <td>***</td>
    <td>Serveur</td>
    <td>Apache 2.0</td>
    <td>Docker Hub</td>
    <td>/</td>
    <td>Dockerfile</td>
    <td>DSL</td>
  </tr>
</table>


