1) Création d'un dossier du nom de voiturePHP

2) Création de la stucture (=> dossier / - fichier)
	-index.php
	=>public
		=>img
		=>css
			-style.css
	=>partials
		-head.php
		-footer.php
		
3) Dans le fichier head.php
	-l'entête
	-nav avec un logo, un nom(votre nom d'entreprise), un lien(home)
	
4) Dans le fichier footer
	-footer avec l'année
	
5) Dans le fichier index
	-faire venir le head
	-faire venir le footer

6) Aller chercher dans google 
	-une image pour le logo
	-5 images de divers voiture

7) Mêttre dans le dossier img

8) Renommer les images pour qu'elle soit plus simple à appeler

9) Envoyer votre code sur github

10) Créer un fichier data.php à la racine
	-Créer un tableau associatif multidimensionnel qui s'appelle Cars
    -Dedans vous devez avoir pour chacune des 5 voitures les clés suivante
    id, name, price, picture 
    dans picture c'est le nom du fichier

11) Dans le fichier index
	-faire venir le fichier data ( Attention il doit être présent sinon le site ne doit pas fonctionner)
    -afficher le tableau voiture grace a vardump

12) Créer un fichier 404.php
	-dedans creer un message d'erreur 
    -et un lien pour retourner vers la page home

13) Dans la page index
	-afficher tous les nom des voitures

14) Dans index
	-afficher les voitures dans une "card" de bootstrap
    avec en titre le nom de la voiture le prix plus bas et un bouton "voir plus"

15) Créer une page car.php
	-dedans faite venir le head et le footer

16) Dans index 
	-Dans bouton des cards modifier le href pour qu'il envoi vers car.php 
    -avec id de la voiture en parametre

17) Dans la page car.php
	-vérifier que vous récupérez bien l'id dans l'url
    -sinon rediriger vers la page 404
    
18) Créer un page function.php
	-créer une fonction qui prend deux paramettres
    -cette fonction doit vérifier que l'id de la voiture existe bien dans le tableau voiture
    - si c'est vrais retourn true sinon false

19) Dans la page car.php 
	-faire venir le fichier data et function
    -si l'id de la voiture existe alors afficher le nom dans un h1
    -sinon mettre un message d'erreur

20) Dans la page car.php
	-afficher l'image

21) Créer une page formulaire
	-faite venir le head et le footer
	-avec les champs suivant : email, prenom, message
    -et un btn envoi

22) Dans la page Index
	-créer un lien vers le formulaire
    
23) Dans la nav
	créer un lien vers formulaire

24) Créer une page formvalide.php
	-faite venir le head et le footer
    -Vérifiez que tous les champs sont rempli sinon créer un message d'erreur
    -Verrifier que l'adresse email est correct, sinon faire un message d'erreur
    -sinon afficher 'Message envoyer' avec un recap des infos email, prénom, message
