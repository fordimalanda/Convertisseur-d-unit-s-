# Convertisseur d'Unités de Mesure

Ce projet est une application en **C** permettant de convertir différentes unités de mesure parmi 16 grandeurs, incluant la longueur, la température, la masse, la vitesse, et bien plus. L'objectif est de fournir une interface simple et efficace pour effectuer des conversions entre une variété d'unités de mesure.

## Grandeurs prises en charge

Le programme prend en charge les conversions suivantes :

1. **Longueur** :
   - Mètre (m)
   
2. **Surface** :
   - Mètre carré (m²)
   
3. **Volume** :
   - Mètre cube (m³)
   
4. **Temps** :
   - Seconde (s)
   
5. **Intensité du courant** :
   - Ampère (A)
   
6. **Masse** :
   - Kilogramme (kg)
   
7. **Température** :
   - Celsius (°C)
   - Kelvin (K)
   
8. **Vitesse** :
   - Mètre par seconde (m/s)
   
9. **Force** :
   - Newton (N)
   
10. **Énergie** :
    - Joule (J)
   
11. **Pression** :
    - Pascal (Pa)
   
12. **Fréquence** :
    - Hertz (Hz)
   
13. **Puissance** :
    - Watt (W)
   
14. **Poids** :
    - Newton (N) *(La force gravitationnelle sur un objet, donc lié à la masse et à la gravité)*
   
15. **Travail** :
    - Joule (J)
   
16. **Accélération** :
    - Mètre par seconde carré (m/s²)

### Fonctionnalités principales

- **Conversion entre unités de longueur**, par exemple : mètre ↔ kilomètre, pouce ↔ pied, etc.
- **Conversion de températures**, comme Celsius ↔ Kelvin.
- **Conversion de masse**, par exemple kilogramme ↔ livre, gramme ↔ once.
- **Conversion de vitesse**, par exemple m/s ↔ km/h, mph ↔ nœud.
- **Conversion de force, énergie, pression, puissance, travail, fréquence, etc.**.
- Interface simple et conviviale accessible via la ligne de commande.

## Installation et Compilation

### Prérequis
- Un compilateur C, tel que **GCC** (GNU Compiler Collection), est nécessaire pour compiler ce programme.
- Assurez-vous d'avoir **GCC** installé sur votre machine. Vous pouvez vérifier si GCC est installé en exécutant la commande suivante dans votre terminal :

   ```bash
   gcc --version
