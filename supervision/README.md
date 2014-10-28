## Supervision avec Nagios
Vous apprendrez à exploiter Nagios efficacement au travers des nombreux travaux pratiques proposés tout au long de la formation. Vous apprendrez à mettre en œuvre une plate-forme de supervision, du paramétrage aux tests des sondes.

### Objectifs
* Comprendre le vocabulaire et la théorie de la supervision d'un réseau
* Comprendre le vocabulaire et les principes de fonctionnements des outils du monde Nagios
* Découvrir les outils de supervision gravitant autour de Nagios
* Mettre en oeuvre une plate-forme de supervision Centreon/Nagios
* Paramétrer et tester les sondes
* Tester les automatisations de paramétrage

### Pré-requis
* Des notions concernant les réseaux et les protocoles
* Des connaissances en administration d'un système d'exploitation GNU/Linux

### Public
* Administrateurs systèmes et réseaux
* Techniciens informatiques désirant mettre en place une solution de supervision

### Durée
* 5 jours

### Prix
* 2500 €

### Programme
1. Supervision : Définitions
  * TP : Partage d'expériences sur les incidents
  * Supervision Passive et Opérationnelle
    * Niveaux d'activité
    * La supervision Opérationelle
      * Composants et étendue de la supervision
      * Acteurs connus
      * Zone couverte par Nagios
    * TP : Éléments supervisables dans un système informatique
    * Pourquoi Superviser ?
  * Méthodes
    * Comment intégrer la supervision dans un processus long et durable
    * Méthodes de mise en place de la supervision
2. Premiers principes de fonctionnement de Nagios
   * HOSTS et SERVICES
   * La gestion des HOSTS et la topologie réseau
     * Topologie : gestion des Incidents Réseaux, relation parent
     * TP : recensement et établissement d'une topologie
     * TP : La topologie jusqu'où ? limites de la relation parent
     * TP : Placer Nagios au sein d'un réseau
   * Le recensements des Hosts
3. Licences libres, fonctionnement des logiciels libres
   * Principes fondamentaux des logiciels libres
   * Open Source, free software, GPL, modèles commerciaux et gestion des communautés
   * TP : discussions ouvertes sur les différents modes de pensée et les impacts des licences libres dans le cycle de vie des projets de supervision
4. Histoire de Nagios et actualités récentes des communautés de supervision libre
   * L'univers Nagios étendu: Shinken, Icinga, Centreon
   * Outils de Supervision annexes
     * Supervision Passive
     * Round Robin Databases (RRD)
     * Cacti et Munin
     * Smokeping
   * Sécurité
     * SNORT et OpenVAS
5. Principes de Fonctionnement de Nagios
   * TP : en parallèle sur tout ce chapitre, découverte des écrans de Nagios et des écrans de Centreon. Manipulations des écrans de supervision, recherches et navigations
   * La délégation de taches et le principe du KISS
   * Les Checks
   * Statut des HOSTS
   * Statut des SERVICES
   * L'ordonnanceur de Commandes
   * Statut HARD/SOFT
   * La gestion des alertes par Nagios
     * Les types d'alertes
     * Le paramétrage des alertes
     * Gestion des périodes de temps et des arrêts planifiés
     * Gestion des dépendances
     * Gestion des escalades
     * Acquittements et Commentaires
     * Le «Flapping»
   * Gestion des Groupes
     * Groupes de Hosts
     * Groupes de Services
   * Modèles de Services et de Hosts
     * Importance de la nomenclature
     * Arborescence de configuration
     * TP : Organiser une configuration
   * Les fichiers de configuration de Nagios
   * Méthode : Factoriser ou recopier
6. SNMP
   * Un protocole standard de supervision
   * Les 3 versions de SNMP
   * Vocabulaire : communauté, MIB, Traps, etc
   * Les MIB et la MIB-II
   * Les outils SNMP
   * TP : utilisation de snmpwalk
   * TP : découvertes des informations de SNMP
   * Les traps et inform SNMP
   * TP : ajout d'un check dans un serveur SNMP
7. Principes de fonctionnement de Nagios
   * Sondes, cheks, commandes de check
   * TP : utilisation de check simples en dehors de Nagios
   * Protocole de communication des Sondes
   * Sondes minimalistes et sondes de tests
   * Arguments courants des sondes
   * Checks Actifs Locaux
     * TP : utilisation de check actifs locaux, intégration dans Nagios avec Centreon
   * Checks Actifs Distants
     * SSH, NRPE, NsClient,SNMP
     * TP : utilisation de check actifs distants, intégration dans Nagios avec Centreon
   * TP : Supervision des disques en SNMP 	10
   * TP : Supervision du traffic réseau en SNMP
   * TP : Supervision distante d'une base de donnée via SSH ou NRPE
   * Les Checks passifs
     * le démon NSCA et le fichier de commandes
     * Fraîcheur et Volatilité
   * Recoller ensemble : Les Checks, les commandes, les services et les hosts
     * Paramétrer les commandes, Arguments et Macros
     * TP : Retour sur les premières commandes, utilisation des arguments
     * Paramétrer les modèles
     * TP : Retour sur les premières commandes, utilisation des modèles
8. Limites de Nagios
   * Supervision distribuée
   * Charge de Supervision
   * NDO : Utilisation d'une base de donnée
     * Équivalents de NDO, exemples de Centreon et MkLiveStatus
9. Superviser Windows : NsClient++ et WMI
   * TP : utilisation de NsClient++
   * TP : utilisation de WMI
10. Nagvis : Nagios sur une carte
   * TP : utilisation de Nagvis
11. De la pratique, encore et toujours
   * TP : Superviser une application Web, retour sur tous les éléments précédents
   * Élements théoriques sur HTTP et HTTPS
12. Centreon : Utiliser les modèles pour générer de la configuration
   * Principes des modèles de génération
   * Comparaison avec un modèle de supervision par gestion de groupes
   * TP : Automatisation des configurations existantes par familles et génération par les modèles
   * TP : Création de nouvelles sondes, cycle complet avec génération par les modèles
   * Méthodes : Retour d'expérience, mettre en place de nouvelles sondes
13. Nagios Exchange
   * Trouver de nouvelles sondes et les installer
   * TP : Parcourir les milliers de sondes et identifier celles qui seront utiles
   * TP : installation d'une sonde externe
14. Utilisations avancées
   * Checks particuliers, check_cluster, check_multi
     * TP : utilisation de check_cluster
   * Supervision Pro Active
     * Principe des gestionnaires d'événements
     * TP : Mise en place d'un redémarrage de service par SSH
     * Éléments théoriques sur NTP et la synchronisation horaire des serveurs
     * TP : Mise en place d'un redémarrage de service par NsClient++
