---
title: "Paramètres de facturation"
short_title: "Facturation"
layout: "default"
lang: "fr"
author: "Thomas GALIBERT"
date: "2017-09-04"
order: 2
category_ref: "parametres"
---

<h1>Voici les différents paramétrages possibles de la facturation : </h1>

<h2>1 - Numérotation ds factures</h2>

<div class="article-img"><img src="https://s3.amazonaws.com/divaveo/screencaptures/param_fact_1.png" alt="Paramètres logiciel Paprs" title="Paramètres logiciel Paprs" /></div>

Comme vous reprenez dans Paprs une comptabilité existante, il est important de reprendre la chronologie de votre ancien système de facturation. Ainsi vous devez renseignez obligatoirement le numéro de début des factures (si vous vous étiez arrété à 180, vous indiquez 181) et des devis.

Vous indiquez après le préfixe de numérotation selon le schéma suivant :

<strong><code>%Y</code> = numéro de l'année, ex : 2017</strong>

<strong><code>%m</code> = numéro du mois, ex : 06</strong>

<strong<code>>%Y</code> = numéro du jour, ex : 23</strong>

Vous pouvez ainsi intercaler des signes comme le tiret '-' ou la barre oblique pour mettre en forme : par exemple :

<code>'%Y/%m/%d - '</code>

donnera une mise en forme du numéro de facture du type : <code>2017/09/14-181</code>

<hr>

<h2>2 - Configuration des emails</h2>

<div class="article-img"><img src="https://s3.amazonaws.com/divaveo/screencaptures/param_fact_2.png" alt="Paramètres logiciel Paprs" title="Paramètres logiciel Paprs" /></div>

Paprs vous donne l'occasion d'envoyer automatiquement vos factures, devis et relances par email à vos clients.

<strong>Par contre, vous ne pouvez pas utiliser directement votre adresse professionnelle ou personnelle pour cela. C'est pourquoi, le courriel que vous allez envoyé sera de la forme :</strong> <code>votreadresse@paprs.co</code>

Vous indiquer alors dans les champs sous quel type d'adresse vous souhaitez communiquer en indiquant seulement le préfixe (la partie avec l'arobase (@)) du style :

<code><strong>facturation.nomdemasociete</strong></code>

<hr>

<h2>3 - Date de paiement</h2>

<div class="article-img"><img src="https://s3.amazonaws.com/divaveo/screencaptures/param_fact_3.png" alt="Paramètres logiciel Paprs" title="Paramètres logiciel Paprs" /></div>

Vous indiquez ici très clairement si vous souhaitez que la date d'exigiblité de la facture soit la date de réception ou un délais particulier exprimé en jours.

<hr>

<h2>4 - Logo de la société</h2>

<div class="article-img"><img src="https://s3.amazonaws.com/divaveo/screencaptures/param_fact_4.png" alt="Paramètres logiciel Paprs" title="Paramètres logiciel Paprs" /></div>

Vous pouvez télécharger un logo (sous forme carré et jpeg de préférence) pour personnaliser l'apparence de vos factures.

<hr>

<h2>5 - Clé secrète</h2>

<div class="article-img"><img src="https://s3.amazonaws.com/divaveo/screencaptures/param_fact_5.png" alt="Paramètres logiciel Paprs" title="Paramètres logiciel Paprs" /></div>

Il s'agit de la clé que vous devez communiquer à votre expert comptable afin que ce dernier puisse accéder à vos données. Il vous suffit de cliquer sur <em><strong>copier la clé</strong></em> pour la mettre dans votre presse-papier
