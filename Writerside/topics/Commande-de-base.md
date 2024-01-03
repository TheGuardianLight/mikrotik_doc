# Commande de base
## Commande de base :

>
> Les quatre commandes de base peuvent être utilisé n'importe où peu importe l'arborescence.
> 
{style="note"}

- `print` : Permet d'afficher la configuration actuelle.
- `set` : Permet de mettre à jour une variable ou une valeur dans une configuration particulière.
- `add` : Permet d'ajouter une configuration.
- `remove` : Permet de supprimer une configuration.

## Commande à faire au démarrage :

Ajouter une interface virtuelle de loopback : `/interface/bridge/add name=lo0`

Donner une ip à l'interface de loopback : `/ip/addresse/add interface=lo0 address=10.10.10.1/32`

Désactiver le client dhcp (dans le cas de la configuration de l'OSPF) : `/ip/dhcp-client/remove 0`

Renommer l'équipement : `/system/identity/set name=`<un_nom>

