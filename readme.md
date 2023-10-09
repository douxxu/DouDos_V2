# DouDos.py

Un outil d'attaque en déni de service (DoS) pour l'éducation et la démonstration.

## Description

DouDos.py est un script Python éducatif qui démontre différentes techniques d'attaques par déni de service (DoS), y compris l'attaque UDP Flood, l'attaque SYN Flood, l'attaque HTTP Flood et l'attaque Ping of Death.

## Fonctionnalités

- **Attaque UDP Flood**: Inonde une cible avec des paquets UDP.
- **Attaque SYN Flood**: Inonde une cible avec des paquets SYN.
- **Attaque HTTP Flood**: Inonde une cible avec des requêtes HTTP.
- **Ping of Death**: Envoie des paquets ICMP de grande taille pour causer un déni de service.

## Utilisation

Pour lancer une attaque, exécutez le script et suivez les instructions :

```bash
python DouDos.py
```

Sélectionnez le type d'attaque que vous souhaitez effectuer en entrant le numéro correspondant.

## Exemple d'utilisation

Voici un exemple d'utilisation pour effectuer une attaque UDP Flood :

1. Lancez le script en exécutant `python DouDos.py`.
2. Choisissez l'option d'attaque UDP Flood en tapant `1`.
3. Suivez les instructions pour fournir l'adresse IP de la cible, le port et le nombre de threads.

## Avertissement

Ce script est destiné à des fins éducatives uniquement. L'utilisation de ces techniques sans autorisation est illégale et contraire à l'éthique. Utilisez ce script de manière responsable et légale.

## Contributions

Les contributions sont les bienvenues ! Si vous souhaitez contribuer, veuillez ouvrir une pull request.

## Licence

Ce projet est sous licence [MIT](LICENSE).
