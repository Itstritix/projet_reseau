# Projet réseau
Voici le document mémoire pour le projet de réseau

# 1. Quantitatif des IP
> Pour le quantitatif des ip, nous avons compté la quantité d'équipements présent sur le plan du futur bâtiment, et la quantité de personnes qui pourrait être présente dans le bâtiment. 
Voici le tableau regroupant le comptage des équipements.
![equipement](/img/equipement.png)
>
> Pour ce qui est des personnes, nous savions qu'il y aurait au maximum 600 personnes, nous avons donc estimé que chaque personne aurait au moins 3 équipements qui seraient connectés au réseau.

> Pour le choix des ips nous sommes parti sur des ip en 10.x.y.y/16 

> **_x_** est le vlan, **_y_** est la parti hôte 

# 2. Choix des équipements
>Pour les équipements nous avons décidé de partir sur les équipements Cisco. Les équipements ont été choisi pour leur capacité à répondre à nos besoins, ils ont aussi été choisi étant donné qu'ils sont récents. 

> - Pour le switch de distribution nous avons décidé de partir sur le modèle : C9300-48U-E 
> - Pour les switch coeur nous avons décidé de partir sur le modèle : C9500-24Y4C-E 
> - Pour les bornes Wi-Fi 6E nous sommes parti sur le modèle : C9130AXI-I

# 3. Datasheet
> ## C9300-48U-E 
>![C9300-48U-E_datasheet_1](/img/9300_datasheet.png)
>![C9300-48U-E_datasheet_2](/img/9300_datasheet_2.jpg)
> Vous pouvez également retrouver la documentation complète du modèle C9300-48U-E >> [ici](https://www.cisco.com/c/en/us/products/collateral/switches/catalyst-9300-series-switches/nb-06-cat9300-ser-data-sheet-cte-en.html) <<

> ## C9500-24Y4C-E 
>![C9500_24Y4C_E_datasheet_1](/img/9500_datasheet.png)
>![C9500_24Y4C_E_datasheet_2](/img/9500_datasheet_2.png)
>![C9500_24Y4C_E_datasheet_3](/img/9500_datasheet_3.png)
>![C9500_24Y4C_E_datasheet_4](/img/9500_datasheet_4.png)
> Vous pouvez également retrouver la documentation complète du modèle C9300-48U-E >> [ici](https://www.cisco.com/c/en/us/products/collateral/switches/catalyst-9500-series-switches/nb-06-cat9500-ser-data-sheet-cte-en.html) <<

# 4. Schéma 
> ## Schéma logique
>![schema_logique](/img/schema_logique.png)
> 
|                   VLAN                   |      IP       |
|:----------------------------------------:|:-------------:|
|                    RH                    | 10.10.0.0/16  |
|                   R&D                    | 10.20.0.0/16  |
|                   DSI                    | 10.30.0.0/16  |
|                   DEV                    | 10.40.0.0/16  |
|                Conception                | 10.50.0.0/16  |
|               Wi-Fi Invité               | 10.60.0.0/16  |
|                Direction                 | 10.70.0.0/16  |
|                   Data                   | 10.80.0.0/16  |
|               Imprimantes                | 10.90.0.0/16  |
|               Logistiques                | 10.100.0.0/16 |
|                  Design                  | 10.110.0.0/16 |
|               Comptabilité               | 10.120.0.0/16 |
|            Sécurité Incendie             | 10.130.0.0/16 |
| Contrôlé d'accès, Intrusion, vidéophonie | 10.140.0.0/16 |
|            Vidéosurveillance             | 10.150.0.0/16 |
|              Système Audio               | 10.160.0.0/16 |



> ## Schéma physique
>![schema_physique](/img/schema_physique.png)

>Il est également possible avec les fichiers présent dans le schema_file, de les ouvrir sur [draw.io](https://app.diagrams.net/)

# 5. Maquette Packet Tracer
> ![maquette](/img/maquette.png)

# 6. DPGF 
> ![img](/img/dpgf.png)

# 7.Document supplémentaire
## Google Sheet
> Il vous est également possible d'accèdez a nos documents en cliquant sur ce lien : [ici](https://docs.google.com/spreadsheets/d/1t6XT5uGQpDeaPIHSy7caQ1djtrR2I6XgD5OMWfYe-BQ/edit?usp=sharing)
