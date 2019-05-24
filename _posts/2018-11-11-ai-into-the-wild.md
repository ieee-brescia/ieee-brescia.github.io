---
layout: post
title: AI into the wild
tags : [Finished Projects]
---

Con il progetto "**AI into the wild**" l'obbiettivo che si è voluto raggiungere è di testare e portare al limite quelle che sono le possibilità di una **CNN** (Convolutional Neural Network) nella risoluzione di un task di *"Face Recognition"*.

## Cos'è una CNN?

Una CNN è una rete neurale convoluzionale, ossia un programma che riesce per mezzo del *machine learning* ad apprendere come distinguere e categorizzare un set di immagini, in base a features che riesce ad estrapolare da un Data-set, secondo tipologie scelte dall'utente. 

## In cosa consiste **AI into the wild**?

Il programma sfrutta due framework largamente usati nel campo dell'Intelligenza artificiale, ***Tensorflow*** e ***OpenCV***.
Il progetto è consistito nel realizzare una rete convoluzionale con Tensorflow che potesse estrapolare features da delle immagini, OpenCV al fine di trovare i volti all'interno di una immagine ed infine tramite il *transfer learning* far si che la rete convoluzionale avesse l'abilità di categorizzare i vari volti.

## Come funziona nel concreto il programma?

Inizialmente all'utente viene richiesto un video di 20 secondi per ogni persona che si vuole che il programma impari a riconoscere. In seconda battuta la rete neurale viene allenata sul dataset fornito (circa 200 immagini per persona, estrapolate dal video) e fornisce una statistica sulla possibile accuratezza. Infine non resta che dare in pasto al programma una foto con una o più persone tra quelle scelte precedentemente e l'algoritmo restituirà in output la foto con un riquadro intorno al viso della persona con il nome al di sotto e, accanto a questo, la percentuale di accuratezza.



![Footer](/images/AI_into_the_wild.png)

## Membri del progetto

Simone Caldarella (Referente) 
[Link] (simone.caldarella.it@ieee.org)

Massimo Bono (Osservatore)
