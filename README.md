# Analyse Cyclistic - Partage de vélos (Google Data Analytics Capstone)

Lien projet : https://lr-analytics.github.io/Google-Data-Analytics-Cyclistic-Case-Study/Projet-fin-d-etude.html
Auteur : Lucas Renaud

Formation : L3 Analyse Économique @ IAE Nantes

Outils : R (tidyverse, ggplot2, lubridate), RMarkdown

# Présentation du projet

Ce projet est le cas pratique final de la certification Google Data Analytics. L'objectif est d'analyser les données historiques de "Cyclistic", une entreprise de partage de vélos à Chicago, afin d'identifier les différences de comportement entre les cyclistes occasionnels et les membres annuels.

L'enjeu stratégique est de fournir des recommandations basées sur les données pour convertir les usagers occasionnels en membres permanents.

# Méthodologie (Processus Data)
L'analyse suit les six étapes du processus d'analyse de données de Google :

Ask (Poser le problème) : Définir la problématique métier et les objectifs de l'analyse.

Prepare (Préparer) : Importation et organisation des jeux de données (données réelles de trajets).

Process (Nettoyer) : Nettoyage des données sous R (gestion des doublons, valeurs manquantes, formatage des dates et durées de trajets).

Analyze (Analyser) : Calcul de statistiques descriptives et agrégation des données par type d'usager, jour de la semaine et saisonnalité.

Share (Partager) : Création de visualisations percutantes avec ggplot2 pour mettre en évidence les tendances.

Act (Agir) : Formulation de recommandations stratégiques.

# Conclusion & Recommandations

L'analyse des données montre que les deux profils de clients ont des habitudes opposées :
L'abonné privilégie l'efficacité avec des trajets courts et réguliers (usage utilitaire).
Le client ponctuel est dans une logique de loisir, avec des trajets souvent deux fois plus longs, particulièrement en fin de semaine.

Recommandation stratégique : Cyclistic ne devrait pas axer sa communication sur la rapidité ou le gain de temps pour cette cible. L'enjeu est de proposer des offres flexibles qui valorisent l'utilisation longue durée et les sorties du week-end, montrant ainsi aux clients occasionnels que l'abonnement est aussi avantageux pour la détente que pour les trajets quotidiens.

# Contenu du dépôt
Analyse_Cyclistic.Rmd : Le code source complet de l'analyse.

Analyse_Cyclistic.html : Le rapport final exporté avec les visualisations et les graphiques.
