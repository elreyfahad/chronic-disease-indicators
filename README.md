# Chronic Disease Indicators Data Analysis

**Les indicateurs de maladie chronique (CDI)** sont un ensemble d'indicateurs de surveillance développés par consensus entre le  **Centre pour le Contrôle et la Prévention des catastrophes (CDC)**, **le Conseil d'État et les épidémiologistes territoriaux (CSTE)** et **l'Association nationale des directeurs des maladies chroniques (NACDD)** des USA. Les CDI permet aux professionnels de la santé publique et aux décideurs de récupérer des données d'état et de métropoles sélectionnées de manière uniforme pour les maladies chroniques et les facteurs de risque qui ont un impact substantiel sur la santé publique. Ces indicateurs sont essentiels pour la surveillance, la priorisation et l'évaluation des interventions de santé publique.

Description des colonnes du dataset:

1. **Topic**: +400k lignes de données qui sont regroupées dans les **17 catégories ou sujets** (**alcool; arthrite; asthme;  cancer; maladie cardiovasculaire; maladie rénale chronique; maladie pulmonaire obstructive chronique; Diabète; immunisation; nutrition, activité physique et poids; santé bucco-dentaire; le tabac; conditions générales**)
2. **TopicID**:une étiquette abrégée des sujets
3. **Question**:Dans chaque sujet, il y a un certain nombre de questions,ce sont les 202 indicateurs uniques de l'ensemble de données
4. **QuestionID**: ID de chaque question
5. **DataSource** : il y ait 33 sources de données
6. **DataValueType** : type des données
7. **DataValue vs DataValueAlt** :la colonne des données qui sera la cible dans notre future analyse,cette colonne se compose de valeurs numériques sous forme chaine de caractere tandis que **DataValueAlt** est composée de valeur numérique en float64.
8. **DataValueUnit** : les unités des valeurs de DataValue (*pourcentages,montants en dollars,années ..etc*)
9. **Stratification and Stratification Category related columns**: Il y a 12 colonnes liées aux stratifications, qui sont des sous-groupes au sein de chaque indicateur tels que **le sexe, la race, l'âge, etc..**. Dans **StratificationCategory1**, il y a **sexe,Overall et la race**. Dans **Stratification1**, les valeurs se composent **des types de race** à titre d'exemple. Dans les colonnes ID telles que **StratificationID1**, nous avons des étiquettes correspondantes pour la race




Notre etude ici,se limite sur les questions suivantes qui concernent les lycéens américains :

1. 'Computer use among high school students',
2. 'Healthy weight among high school students',
3. 'Median daily frequency of fruit consumption among high school students',
4. 'Median daily frequency of vegetable consumption among high school students',
5. 'Meeting aerobic physical activity guidelines among high school students',
6. 'Obesity among high school students',
7. 'Overweight or obesity among high school students',
8. 'Participation in daily school physical education classes among high school students',
9. 'Soda consumption among high school students',
10. 'Television viewing among high school students'
