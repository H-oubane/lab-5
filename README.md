# Lab 5 Android – Convertisseur avec Onglets

Application Android avec 2 onglets réalisée avec Android Studio en Java.

## Objectif
Créer une application de conversion avec onglets :
- Onglet **Température** : Celsius ↔ Fahrenheit
- Onglet **Distance** : Km ↔ Miles
- Boîte de dialogue de confirmation avant de quitter

## Captures d'écran

### 1. Onglet Température (25°C → 77°F)

<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/592ba65e-0713-487d-a010-ef8898cb8b65" />


### 2. Onglet Distance (10 Km → 6.21 Miles)

<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/bfdfd398-c212-4be1-a811-0756b2be3047" />


### 3. Boîte de dialogue Quitter

<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/f240a49f-2c93-4b5d-b933-a0ae438c2962" />


## Structure du projet
```
ConverterTabsJava/
 └── app/src/main/
      ├── java/com/example/convertertabsjava/
      │    ├── MainActivity.java       → Activité principale + onglets
      │    ├── ViewPagerAdapter.java   → Adaptateur des fragments
      │    ├── TempFragment.java       → Fragment Température
      │    └── DistanceFragment.java   → Fragment Distance
      └── res/layout/
           ├── activity_main.xml       → UI principale
           ├── fragment_temp.xml       → UI Température
           └── fragment_distance.xml   → UI Distance
```

## Auteur
**H-oubane**
