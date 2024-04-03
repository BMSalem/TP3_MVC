<h3>Compte Rendu TP3 Partie 1</h3>
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