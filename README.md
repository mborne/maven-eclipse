# Configuration eclipse/maven avec un proxy

ATTENTION : Cette méthode est destinée à un TP.

## Configuration du proxy

Dans le fichier /etc/maven/settings.xml, définir les lignes suivantes :

![mvn-proxy.png](mvn-proxy.png)


## Test de maven en ligne de commande

```
git clone https://github.com/mborne/spring-ioc-principe.git
cd spring-ioc-principe
mvn clean package
```

## Configuration d'eclipse

Voir window/preference, onglet maven

### Utilisation de maven installé dans le système

![mvn-eclipse-01.png](mvn-eclipse-01.png)

### Définition du fichier de paramètres maven

![mvn-eclipse-02.png](mvn-eclipse-02.png)

## Test dans eclipse

Via Fichier/import, on peut importer un projet maven existant :

![mvn-import-01.png](mvn-import-01.png)

... puis sélection du dossier contenant le pom.xml
