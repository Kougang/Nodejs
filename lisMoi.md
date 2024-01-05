lien du site d'entrainement: https://nodejs.developpez.com/tutoriels/javascript/node-js-livre-debutant/

ce fichier contient la description du mechanisme de fontionnement de ce bout de code nodejs, en effet le fichier index.js est ;e fichier qui se lance par defaut, dans ce fichier nous appelons le module en exportation requestHandler puis nous importons egalement le module router.js et sever.js.
lorsque nous recevons une action, nous le passons dans le serveur a partir du fichier index.js puis le serveur nous rediriget vers le fichier router.js qui nous permettra d appeler ;a methode adequat dans le fichier requestHandler pour sont execution.
on a egalement la possibilite de remonter un message de requestHandler en passant par le routeur pour arriver au serveur et afficher le message en question
