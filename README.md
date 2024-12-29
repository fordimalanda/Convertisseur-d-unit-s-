# Convertisseur d'Unités de Mesure en C

Ce projet est une application en **C** permettant de convertir différentes unités de mesure parmi 16 grandeurs, incluant la longueur, la température, la masse, la vitesse, et bien plus. L'objectif est de fournir une interface simple et efficace pour effectuer des conversions entre une variété d'unités de mesure.

## Grandeurs prises en charge

Le programme prend en charge les conversions suivantes :

1. **Longueur** :
   - Mètre (m)
   - Kilomètre (km)
   - Centimètre (cm)
   - Millimètre (mm)
   - Pouce (in)
   - Pied (ft)
   - Yard (yd)
   
2. **Température** :
   - Celsius (°C)
   - Fahrenheit (°F)
   - Kelvin (K)
   
3. **Masse** :
   - Kilogramme (kg)
   - Gramme (g)
   - Milligramme (mg)
   - Livre (lb)
   - Once (oz)
   
4. **Vitesse** :
   - Mètre par seconde (m/s)
   - Kilomètre par heure (km/h)
   - Mile par heure (mph)
   - Nœud (kn)

### Fonctionnalités principales

- **Conversion entre unités de longueur**, par exemple : mètre ↔ kilomètre, pouce ↔ pied, etc.
- **Conversion de températures**, comme Celsius ↔ Fahrenheit ↔ Kelvin.
- **Conversion de masse**, par exemple kilogramme ↔ livre, gramme ↔ once.
- **Conversion de vitesse**, par exemple m/s ↔ km/h, mph ↔ nœud.
- Interface simple et conviviale accessible via la ligne de commande.

## Installation et Compilation

### Prérequis
- Un compilateur C, tel que **GCC** (GNU Compiler Collection), est nécessaire pour compiler ce programme.
- Assurez-vous d'avoir **GCC** installé sur votre machine. Vous pouvez vérifier si GCC est installé en exécutant la commande suivante dans votre terminal :

   ```bash
   gcc --version

