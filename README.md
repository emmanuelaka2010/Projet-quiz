# Projet-quiz
Le Projet-quiz consiste à modéliser la base de donnée d'une application qui permet de faire des quiz.

La base de donnée de contient 7 tables à savoir les tables: user, score, module, stage, niveau, stage, question et réponse.

## Les 7 tables:

## user
- id
- nom
- prenom
- email

## module
- id
- nom_module

## stage
- id
- nom_stage
- id_module

## niveau
- id
- nom_niveau
- id_stage

## question
- id
- question
- id_niveau

## reponse
- id
- reponse
- id_question
