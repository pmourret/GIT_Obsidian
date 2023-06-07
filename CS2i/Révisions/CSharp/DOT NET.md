- [ ] Principes MVC sous Windows Forms
- Model View Controller
	- Model -> Définit les données (Ex : Un objet voiture)
	- Controler -> Récupére les actions transférés par la View et interragit avec le modèle puis modifie la view en fonction des actions demandées
	- View -> Interface graphique 
	- **Une view et un Controler sont quasiment identiques en C#**
- [ ] Composants graphiques principaux
	- [ ] TextBox
	```cs
		var textBox = new TextBox();
	```
	- [ ] Button
	```cs
		var button = new Button();
	```
	- [ ] PictureBox
	```cs
		var pictureBox = new PictureBox();
	```
- [ ] Containers
	- [ ] Formulaire
	- [ ] UserControl
		- Un UserControl permet de créer un contrôle vide dans lequel il est possible de renseigner différents éléments pouvant être réutilisés 
			- Ex : Un formulaire d'inscription 
	- [ ] Panel
	- [ ] FlowLayoutPanel
	- [ ] Collection `Controls` des containers
- [ ] Notion de fichier `.designer.cs` 
- [ ] Construction d'une interface graphique de façon dynamique
	- [ ] TP des X boutons à générer
	- [ ] Démineur et création de la BoardView
- [ ] Boîte de dialogue de base
- [ ] Sorties d'aide au débugage
- [ ] Gestion des ressources images
	- [ ] Intégrer les images au projet
	- [ ] Exploiter les images
- [ ] Brancher un listener sur un objet
	- [ ] Depuis l'interface graphique
	- [ ] Par code
	- [ ] Signature standard d'un listener 