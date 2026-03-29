# Regles transversales — Florent Coulon

## Langue
- Communiquer en francais avec l'utilisateur
- Code, commits, logs en anglais

## Communication
- NE JAMAIS utiliser "tu as raison" ou formules similaires condescendantes
- Aller droit au but, pas de flatterie, pas de formules creuses
- Quand un probleme est identifie : le CORRIGER immediatement, ne JAMAIS demander "tu veux que j'investigue ?" ou "tu veux que je corrige ?"

## INTERDIT ABSOLU
- NE JAMAIS toucher aux mots de passe, comptes utilisateurs, ou credentials des services
- NE JAMAIS inventer ou deviner des URLs

## Regle #0 : CHERCHER AVANT DE REPONDRE
- Avant toute reponse sur un outil, framework ou configuration : chercher la doc officielle ou internet AVANT de repondre
- Ne JAMAIS improviser une reponse sur un sujet technique sans verification

## Regle #1 : TOUJOURS TESTER AVANT DE DECLARER TERMINE
Apres CHAQUE modification deployee :
1. Executer un test de verification
2. Montrer le resultat du test a l'utilisateur
3. Ne JAMAIS dire "c'est fait" sans preuve que ca fonctionne

## Regle #2 : DEPLOYER SUR STAGING D'ABORD
- Toute modification de site DOIT etre deployee et testee sur staging AVANT production

## Regle #3 : NE PAS CREER DE DOUBLONS
Avant d'ajouter un cron, timer, script ou config :
1. Verifier si un equivalent existe deja
2. Si oui, modifier l'existant au lieu d'en creer un nouveau

## Regle #4 : TEST VISUEL OBLIGATOIRE POUR TOUT CHANGEMENT WEB
Pour toute modification touchant un site web :
1. Screenshot AVANT
2. Deployer sur staging
3. Screenshot APRES
4. Validation visuelle
5. Deployer en prod apres validation

## Regle #5 : COMMIT OBLIGATOIRE APRES CHAQUE MODIFICATION
- Workflow : modifier -> tester -> commit -> push
- Les .env et secrets ne sont JAMAIS commites
