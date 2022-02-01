# GPS 2 GIS

## QU'EST-CE QUE C'EST ?
Un projet Android qui utilise la base de donnée GIS Spatialite pour illustrer le cour sur Android à l'ENSG.
La documentation suivante est un didacticiel qui vous permet de créer votre projet Android avec spatialite.

## PURPOSE (EN)

[sevar83](https://github.com/sevar83/android-spatialite/blob/master/README.md) redit:
- When you need deployment, collecting, processing and fast querying of small to huge amounts of geometry data (points, polylines, polygons, multipolygons, etc.) on Android devices.
- When you want to be 100% independent from any server/cloud backend.

## DIDACTICIEL

### ETAPE 1 - Creation du projet
**TO BE CONTINUED**

### ETAPE 2 - Configurer la librairie dans Gradle
1) Ajouter le repository jitpack dans le fichier `settings.gradle` du projet :

```groovy
maven { url "https://jitpack.io" }

```

Ce qui doit donner les quelques lignes suivantes :

```groovy
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        // ....
        maven { url "https://jitpack.io" }
    }
}
```

2) Ajouter la dépendance au package android-spatialite dans le fichier `build.gradle` du module :
```groovy
implementation 'com.github.sevar83:android-spatialite:2.0.1'

```

Ce qui doit donner les lignes suivantes :

```groovy
dependencies {

    // ...

    implementation 'com.github.sevar83:android-spatialite:2.0.1'

}

```

