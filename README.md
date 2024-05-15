# Benin_Langue_local_text_vers_image

![jnr9pwte](https://github.com/Hop-Syder/Benin_Langue_local_text_vers_image/assets/51538739/5030db8e-2113-4033-92fc-8efc8ad6f023)

# Générateur d'images à partir de texte en langue locale
Ce projet est un générateur d'images à partir de texte en langue locale qui permet aux utilisateurs de générer des images basées sur des invites de texte en langues Yoruba ou Française. Il utilise l'API Google Translate pour traduire les invites en anglais, puis génère des images en utilisant le modèle Dall-E 3.

# Fonctionnalités
    Sélection de la langue d'entrée : Choisissez entre les langues Yoruba et Française pour l'invite de texte.
    Invite de texte : Entrez une invite de texte dans la langue sélectionnée pour générer une image.
    Génération d'image : L'application traduit l'invite en anglais en utilisant l'API Google Translate et génère une image en utilisant le modèle Dall-E 3.
    Affichage du résultat : L'image générée est affichée dans l'application.
    Construction à partir de zéro

# Pour commencer avec ce projet, suivez ces étapes :

   Créez un compte sur Windmill
   Créez une nouvelle application
   Incluez des composants de sélection d'entrée, d'entrée de texte, de bouton et d'image
   Ajoutez le contenu de inline_script.py dans le script en ligne du bouton
   Configurez les variables d'environnement
   Testez
   
# Copypasta
   Créez un compte Windmill
   Copiez le contenu du fichier hub_compatible_json.json
   Cliquez sur Importer à partir de JSON
   Collez le hub_compatible_json.json
   Testez
   
# Utilisation
   Sélectionnez la langue d'entrée souhaitée (Yoruba ou Française) dans le menu déroulant.
   Entrez une invite de texte dans la langue sélectionnée dans le champ d'entrée de texte.
   Cliquez sur le bouton "Press me" pour lancer le processus de génération d'image.
   L'image générée sera affichée dans l'application.
   Comment ça marche
   L'application suit ces étapes pour générer des images à partir d'invites de texte en langue locale :

L'utilisateur sélectionne la langue d'entrée (Yoruba ou Française) et entre une invite de texte.
Lorsque le bouton "Générer l'image" est cliqué, l'application envoie la langue sélectionnée et l'invite de texte au backend.
Le backend utilise l'API Google Translate pour traduire l'invite de texte de la langue sélectionnée en anglais.
L'invite traduite en anglais est ensuite passée au modèle Dall-E 3 pour générer une image.
L'URL de l'image générée est renvoyée au frontend et affichée dans l'application.
Contribuer

Source : conversation avec Bing, 15/05/2024
(1) Google Translate. https://translate.google.com/.
(2) DeepL Translate: The world's most accurate translator. https://www.deepl.com/translator.
(3) Translate from english to french online - Yandex Translate. https://translate.yandex.com/en/translator/English-French.
(4) Lingvanex | FREE Online English to French Translator.. https://lingvanex.com/translation/english-to-french.
(5) English-French Dictionary - WordReference.com. https://www.wordreference.com/enfr/.
