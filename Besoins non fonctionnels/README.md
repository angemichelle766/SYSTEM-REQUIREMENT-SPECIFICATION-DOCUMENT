Cahier des Charges – Besoins Non Fonctionnels
1. Performance
Objectifs : Temps < ouverture 3s au plus, au moins 500 utilisateurs , disponibilité 99%. Réalisation : Cache (Redis), backend optimisé (Spring/Django/Express), SQL indexé, minification
front, load balancing, cloud + monitoring, réplication BDD.
2. Sécurité
Objectifs : Authentification forte, données protégées. Réalisation : JWT/OAuth2, HTTPS, hachage scrypt, chiffrement AES-256, logs (ELK), backups
quotidiens + tests.
 3. Fiabilité
Objectifs : Continuité du service. Réalisation : Transactions ACID, sauvegarde locale temporaire, serveur secondaire, validations
strictes.
4. Compatibilité
Objectifs : Fonctionne partout. Réalisation : HTML5/ES6, responsive mobile, API REST + Swagger.
 5. UX / Ergonomie
Objectifs : Interface simple et accessible. Réalisation : UI légère (Material/Bootstrap), prototypes Figma, WCAG 2.1, i18n JSON.
 6. Maintenabilité
Objectifs : Code durable et clair. Réalisation : MVC/microservices, documentation Swagger/UML, tests (JUnit/Jest/PyTest), CI/CD.
 7. Scalabilité / Portabilité
Objectifs : Facile à faire grandir. Réalisation : Docker, CI/CD, architecture modulaire, Redis distribué, PostgreSQL.
 8. Audit / Confidentialité
Objectifs : Traçabilité + protection. Réalisation : RBAC strict, aucune donnée sensible côté front, triggers SQL + logs Kibana.
9. Conformité
Objectifs : Respect des règles. Réalisation : Politique de confidentialité, masquage données, consentement, conservation limitée. Résumé final (1 phrase)
Application rapide, sécurisée, fiable, compatible, scalable et conforme, avec des solutions
techniques simples pour chaque exigence.
