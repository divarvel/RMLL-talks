:Info: Contribution des Étudiants de l'École Centrale de Nantes à MarkUs, un projet libre
:Auteur: Clément Delafargue <clement@delafargue.name>
:Auteur: Nelle Varoquaux <nelle.varoquaux@gmail.com>
:Auteur: Benjamin Vialle <benjaminvialle@gmail.com>
:Auteur: Morgan Magnin <morgan.magnin@ec-nantes.fr>
:Revision: $Revision: 0 $
:Date: $Date: 9-14 juillet 2011 $

==================================================================================
Contribution des Étudiants de l'École Centrale de Nantes à MarkUs, un projet libre
==================================================================================

.. contents::

.. RAPPEL

.. MarkUs [1] est une application web écrite en Ruby on Rails destinée à
.. l'évaluation du code source produit lors des TPs d'informatique, en classe.
.. MarkUs a été découvert lors des stages ingénieurs de deux étudiants à
.. l'Université de Toronto, au Canada. Depuis janvier 2010, plusieurs élèves de
.. l'École Centrale de Nantes ont travaillé sur des projets académiques visant
.. d'une part à adapter le logiciel aux spécificités du système universitaire
.. français, d'autre part à l'enrichir de nouvelles fonctionnalités. Plusieurs de
.. ces projets se sont enchaînés, effectués en binôme ou par groupe de 6 élèves
.. pendant 3 mois.

L'École Centrale de Nantes et le Libre
================================================================================

OpenOffice.org / OpenOffice4Kids
--------------------------------------------------------------------------------

- Participation au développement d'OpenOffice.org et d'OpenOffice4Kids depuis 3
  ans grâce à plusieurs projets étudiants

MarkUs
--------------------------------------------------------------------------------

- Utilisation de MarkUs pour améliorer l'enseignement de l'informatique
- Projets scolaires d'ajout de fonctionnalités au logiciel

MarkUs
================================================================================

.. Très rapide

Constat
--------------------------------------------------------------------------------

Comment gérer et évaluer efficacement les travaux des étudiants en TP/Projet ?

Enseignants :

- Gros volume de soumissions à traiter (plusieurs centaines par TP)
- Difficulté d'harmonisation des facteurs de correction d'un chargé de TD/TP à
  l'autre
- Retour des dossiers aux étudiants

.. Gestion papier :
    Amoncellement de piles
   Gestion par courriels :
    Erreurs dans le destinataire
    Archives .zip illisibles
    Lourdeurs

Étudiants :

- Difficulté pour récupérer/consulter ses travaux corrigés
- Gestion papier

..  Perte de rapports

- Gestion par courriels :

.. Erreurs dans le destinataire
.. Un courriel parmi d'autres


MarkUs
--------------------------------------------------------------------------------

- Application Web
- Initialement destinée à l'évaluation en informatique
- Dépôt (versionné) des travaux étudiants
- Annotation directe des documents par les enseignants

Un projet fait par des étudiants, encadré par des étudiants
================================================================================

Un projet initié par des professeurs:
--------------------------------------------------------------------------------

- Initié par Pr. Karen Reid (UofT)
- encadré par des professeurs (UofT, UofW, ECN)
- nouvelles fonctionnalités proposés par des professeurs

=> les clients sont des profs

Mais, développé uniquement par des étudiants
--------------------------------------------------------------------------------

.. Plus de 1000 commits, 0 fait par des professeurs

- Une équipe de 4 core dev (anciens étudiants)
- Des équipes trimestrielles/semestrielles d'étudiants

Comparaison par rapport à un projet OS "normal"

=> Turnover des dév très important
=> difficulté de maintenir une équipe stable
=> projet non communitaire, mais dirigé par les demandes du client (même si
   une certaine flexibilité de la part des professeurs encadrant)
=> projet encadré par des personnes qui n'ont souvent jamais vu une seule
   ligne de code de Markus

Un impact sur la qualité du code ?
--------------------------------------------------------------------------------

Été 2009, revue de code par Mike Gunderloy, qui juge le code "de meilleurs
qualités que la plupart des projets professionnels qu'il a vu

=> Description du processus d'assurance qualité

Impact sur l'organisation du projet ?
--------------------------------------------------------------------------------

Deux types d'encadrant:
- le professeur, chargé de l'évaluation des élèves
- les mentors techniques, chargé d'aider les élèves avec la partie technique.

- revue de code et encadrement de la part de professionel (Mike Gunderloy -
  Rails, Adam Goucher - QA, Karen Reid - management de projet etc)
- Processus d'assurance qualité élaboré.

Un projet canadien, importé en France
================================================================================

.. insisté sur le côté internationnal du projet


UCOSP: Undergraduate Capstone Open Source Projects
--------------------------------------------------------------------------------

Centrale Nantes au sein du projet
--------------------------------------------------------------------------------

Un premier stage, une première prise de contact avec l'équipe canadienne...
Puis des projets étudiants, un deuxième stage, et finalement, une première
utilisation.

Un projet fortement international: quel impact sur l'organisation ?
--------------------------------------------------------------------------------

- forte présence sur IRC
- communication par mail

Utilisation de Markus à Centrale Nantes
================================================================================

Un projet étudiant typique à Centrale Nantes
--------------------------------------------------------------------------------

- Ecriture d'un cahier des charges
- Implémentation de fonctionnalité
- Redaction de rapport hebdomadaire
- Réunion hebdomadaire(?) avec l'encadrant
- Rédaction d'un rapport final
- Présentation de 20min

Markus parmi les projets centraliens
--------------------------------------------------------------------------------

.. faire un beau schéma
Identification des fonctionnalités => Ecriture d'un cahier des charges par les
étudiants => Implémentation => Assurance Qualité => Intégration du code dans
Markus

**deux étapes supplémentaires**: l'identification des fonctionnalités &
l'assurance qualite


Conclusion
================================================================================

Listes des fonctionnalités implémentées par des étudiants ECN dans Markus:

- Gestion des groupes - invitation des étudiants (Nelle Varoquaux)
- Refonte de l'interface utilisateur (Nelle Varoquaux)
- Framework de test (Benjamin Vialle)
- Implémentation des sections (Nelle Varoquaux & Christian Jacques)
- Internationalisation & traduction en français (Benjamin Vialle)
- Ajout d'un module d'annotation tactile (Clément delafargue, Benjamin Vialle
  etc) *en cours*
- Ajout d'un module d'annotation de formule mathématiques (Anthony Le Jalle
  Mickael Lumbroso) *en cours*
- Ajout d'un module de détection de plagiat (Shion Kashimura & Benjamin
  Thorrent) *en cours*
- Migration à rails 3 (Benjamin Vialle) *en cours*

