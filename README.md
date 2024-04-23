<h2>Compte Rendu TP3 Partie 1</h2>
<p>
Spring MVC Architecture<br>
<center><img src="assets/0.png"></center>

1-Afficher les patients:<br>
Entity Patient:
<center><img src="assets/Code_Patient.PNG"></center>

Patient Repository:
<center><img src="assets/Patient_Repo.PNG"></center>

Patient Controller:
<center><img src="assets/Patient_Control3.PNG"></center>

Hopital Application:
<center><img src="assets/Hotel_Application1.PNG"></center>
<center><img src="assets/Hotel_Application2.PNG"></center>

Affichage des patients dans une template Thymeleaf:
<center><img src="assets/Thymleaf1.PNG"></center>
<center><img src="assets/Thymleaf2.PNG"></center>

Resultat:
<center><img src="assets/Bootstrap_Patient.PNG"></center>

2-La pagination:
Affichage:
Ajouter 'size' et 'page' dans le Controlleur
<center><img src="assets/Pagination.PNG"></center>
la barre de pagination dans htlm
<center><img src="assets/Pagin_bar.PNG"></center>
Resultat:
<center><img src="assets/Index_Final.PNG"></center>

3-Chercher les patients:
Ajout du formulaire de recherche
<center><img src="assets/Recherche_Patient.PNG"></center>

Ajout de la methode "findByNomContains" dans Patient Repository
<center><img src="assets/findby.PNG"></center>

Ajout du mot keyword dans la barre de pagination
<center><img src="assets/Recherche_Patient.PNG"></center>

Ajout du parametre keyword dans Patient Controller
<center><img src="assets/Patient_Control3.PNG"></center>

Resultat:
<center><img src="assets/Index_Final.PNG"></center>

4-Supprimer un patient:
Ajouter un boutton delete dans "patients.html" avec une confirmation Onclick
<center><img src="assets/Delete_Patient.PNG"></center>

Créer la methode delete dans le controller et faire une redirection vers index
<center><img src="assets/Delete_redirect.PNG"></center>
Resultat:
<center><img src="assets/Del1.PNG"></center>
<center><img src="assets/Del2.PNG"></center>
<center><img src="assets/Del3.PNG"></center>

<h2>Partie 2</h2>
<h3>1-Créer une page template</h3>
<img src="assets/template1.PNG">
<img src="assets/template2.PNG">
Résultat:
<img src="assets/Drop_DownList.PNG">

<h3>2-Ajout d'un formulaire et de la méthode save:</h3>
<img src="assets/HTML_Formulaire.PNG">
<img src="assets/Patient_save.PNG">
Résultat:
<img src="assets/Formulaire_Patient.PNG">


<h3>3-Tester l'ajout d'un patient à partir du formulaire:</h3>
<img src="assets/Formulaire_Ajout.PNG">
<img src="assets/ajout_Patient.PNG">

<h3>4-Faire la validation du formulaire:<br></h3>
+ Ajout des dépendances
  <img src="assets/Validation.PNG">
+ Ajout des Annotations à la classe Patient:
  <img src="assets/Class_Patient_Valid.PNG">
+ Ajout de l'annotation Valid au Controller:
  <img src="assets/Valid_annot.PNG">

<h3>5-Ajout du formulaire d'édition:</h3>
<img src="assets/Edit_HTML.PNG">
Résultat
<img src="assets/Edit_Final.PNG">
<img src="assets/Apres_Edit.PNG">





