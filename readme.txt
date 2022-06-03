projet architecture kubernetes


Ajout du load-balancer, du HPA et des pods via l'outils Helm.
L'outils permet d'ajouter directement toutes l'infrastructure grâce aux templates déjà préparés.
On a juste à modifié le template pour qu'il soit en accord avec nos besoins.


penser à lancer minikube tunnel pour avoir l'external IP du cluster.
lancer les commandes de helm
helm install lb load-balancer

puis upgrade avec le lb-values.yaml que l'on a modifié.
