# Codev Recherche

Codev-Recherche est un projet de recherche mené par un étudiant de l'IMT Atlantique, sous la supervision de l'un des enseignants-chercheurs de l'école. Ce projet a pour objectif de reproduire et valider les résultats d'un ou plusieurs articles de recherche existants.

Dans ce cadre, j'ai réalisé mon projet sous la supervision du Professeur Lucas Drumetz, dans le domaine des réseaux de neurones informés par la physique (Physics-Informed Neural Networks ou PINNs), et plus particulièrement dans l'étude des réseaux de neurones hamiltoniens dissipatifs (Dissipative Hamiltonian Neural Networks).

Une des améliorations que nous avons apportées au modèle est l'apprentissage à partir d'une vidéo YouTube en utilisant le finetuning de YOLOv7. J'ai crée et annoter la base de donnée d'entrainnement disponible [ici](https://universe.roboflow.com/pendulum/ccprime/browse?queryText=&pageSize=50&startingIndex=0&browseQuery=true).

Voici une démonstration du résultat du modèle YOLOv7 : [Demo](https://github.com/lha2023/Codev-Recherche/blob/main/Outputs/Output%20YoloV7.mp4).

J'ai réussi à reproduire les résultats du premier article proposé par mon encadrant, mais lorsque nous avons appliqué ce modèle sur des données extraites d'une vidéo, la méthode s'est révélée moins efficace. J'ai donc recherché un autre article pour résoudre ce problème : Learning Hamiltonians from Noisy and Sparse Data, ce qui a abouti à des résultats très surprenants.

Le rapport [Suivant](https://github.com/lha2023/Codev-Recherche/blob/main/Rapport%20CODEV%20Recherche.pdf) présente une comparaison des trois modèles afin d'évaluer leur efficacité respective.
