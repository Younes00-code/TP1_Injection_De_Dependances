Objectif
Ce TP a pour but de mettre en œuvre les concepts d’injection de dépendances (IoC) en Java à travers :

Une première partie reproduisant les exemples vus en cours/vidéo,

Une deuxième partie consistant à concevoir un mini framework d’injection de dépendances similaire à Spring IoC.

Partie 1 — Reprise du support de cours et vidéo

1 Création de l’interface IDao
2 Implémentation concrète de l’interface
3 Création de l’interface IMetier
4 Implémentation MetierImpl avec injection via interface IDao
5 Injection des dépendances   (   Par instanciation statique  & Par instanciation dynamique (réflexion) Avec le Framework Spring Version XML )
![image](https://github.com/user-attachments/assets/17dc5576-c32c-4e1b-9558-872853320df9)
![image](https://github.com/user-attachments/assets/ac5b1abc-ec11-4006-93c9-49757571d905)
![image](https://github.com/user-attachments/assets/a61352e8-7b7a-4e4c-a93e-93cbaf9865df)

Partie 2 — Mini Framework d’Injection de Dépendances

1 Injection par XML (JAXB + réflexion)
2 Injection par annotations personnalisées
3 Trois types d’injection supportés( Par constructeur : via @InjectByConstructor  & Par setter :XML <property>  & Par champ (Field) : via @InjectByField )

![image](https://github.com/user-attachments/assets/8e0ea212-1a8c-462c-8094-5fe3ae525906)
![image](https://github.com/user-attachments/assets/cd1cef79-3143-4b12-b078-5d7bf8fd9ea1)
![image](https://github.com/user-attachments/assets/86e08558-4731-4c3a-81cc-f22443b31217)
![image](https://github.com/user-attachments/assets/99183236-a4fd-426c-bf5f-70280e432052)

version JAVA : 21
IDE : IntelliJ IDEA





