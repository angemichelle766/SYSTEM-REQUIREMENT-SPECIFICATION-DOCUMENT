     Les objectifs techniques pertinants pour la gestion des notes sont:
A-Gestion des donnees:
-stokage securise: utiliser une base de donnees relationnelle(postsgreSQL) pour gerrer les notes,utilisateurs matieres.
-sauvegarde automatique:implementer des sauvegardes regulieres des donnees
B-Authentification et securite:
-connexion securisee:authentification avec OAuth,JWT
-Controle d'acces: gesrion des roles( etudiants ,enseignants,admin) avec des permisions specifiques.
- Chiffrement des donnees :proteger les notes sensibles avec avec HTTPS et chiffrement de donnes stokees
C-Interface utilisateur:
-Responsive design: application accessible sur mobile tablette,ordinateur
- Experience intuitive: navigation claire,saisie rapide des notes
- notifications: alertse pour les mises a jour des notes , echeances.
D-Fonctionnalites principales
  -Creation/modification/suppression des notes avec possibilite de categoriser(matiere,date)
  -calcul de moyenne:automatiser le calcul des moyennes par matire ou semestre
  -Export/import: permettre  l'export en PDF/Excel et l'import des fichiers
E- Performances et scalabilite:
  -Optimisation des requetes:reduire les temps de chargement,gerer un grand nombre d'utilisateur
  - Deploiement cloud:utiliser un hebergementscalable(AWS,Heroku)
F-Maitenance et evolutivite
  -APIRESTful: faciliterl'integration avec d'autres services
  -test automatises: mettre en place des tests unitaires et d'integration
G-Accessibilite
  -support multilingue francais,anglais
  -Compatibilite navigateurs:fontionner sur les principaux navigateurs( chrome,firefox,safari)

  PAR:Ange michelle

