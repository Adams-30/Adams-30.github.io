<!DOCTYPE html>
<html langue="fr">
<tête>
    <méta jeu de caractères="UTF-8">
    <méta nom="fenêtre d'affichage"contenu="largeur=largeur-de-l'appareil, échelle-initiale=1,0">
    <titre>Formulaire d'inscription</titre>
    <lien rel="feuille de style"href="styles.css">
</tête>
<corps>
    <div classe="formulaire-conteneur">
        <!-- Logo -->
        <div classe="logo-conteneur">
            <image source="https://media.istockphoto.com/id/1331164844/vector/star-shoes-logo-template-design.jpg?s=612x612&w=0&k=20&c=DIS6yk7txA__kgArWpGkETJ8aIoOBvxInP2OWw-n6yc="autre="Logo de l'entreprise"classe="logo">
        </div>

        <!-- Formulaire d'inscription -->
        <h2>Inscription</h2>
        <formulaire action="/inscription"méthode="POSTE">
            <div classe="groupe de forme">
                <étiquette pour="nom">Nom complet</étiquette>
                <saisir taper="texte"identifiant="nom"nom="nom"espace réservé="Entrez votre nom"requis>
            </div>

            <div classe="groupe de forme">
                <étiquette pour="e-mail">Adresse e-mail</étiquette>
                <saisir taper="e-mail"identifiant="e-mail"nom="e-mail"espace réservé="Entrez votre e-mail"requis>
            </div>

            <div classe="groupe de forme">
                <étiquette pour="motdepasse">Mot de passe</étiquette>
                <saisir taper="mot de passe"identifiant="motdepasse"nom="motdepasse"espace réservé="Créez un mot de passe"requis>
            </div>

            <div classe="groupe de forme">
                <étiquette pour="confirmation_motdepasse">Confirmez le mot de passe</étiquette>
                <saisir taper="mot de passe"identifiant="confirmation_motdepasse"nom="confirmation_motdepasse"espace réservé="Confirmez votre mot de passe"requis>
            </div>

            <bouton taper="soumettre">S'inscrire</bouton>
            
        </formulaire>
    </div>
</corps>
</html>
