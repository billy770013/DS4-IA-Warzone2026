Aimmy est un mécanisme universel d'alignement de la visée basé sur l'IA, développé par BabyHamsta, MarsQQ et Taylor pour rendre le jeu plus accessible aux utilisateurs ayant des difficultés à viser.

Contrairement à la plupart des mécanismes d'alignement de visée basés sur l'IA, Aimmy utilise DirectML, ONNX et YOLOV8 pour détecter les joueurs, offrant ainsi une précision et des performances supérieures à celles des autres systèmes d'alignement de visée, notamment sur les GPU AMD, qui ne seraient pas performants avec les mécanismes d'alignement de visée utilisant TensorRT.

Aimmy offre également une interface utilisateur facile à utiliser, un large éventail de fonctionnalités et d'options de personnalisation, ce qui fait d'Aimmy une excellente option pour tous ceux qui souhaitent utiliser et adapter un mécanisme d'alignement de visée pour un jeu spécifique sans avoir à coder.

Aimmy est entièrement gratuit. Cela signifie qu'il n'y a ni publicité, ni système de clés, ni fonctionnalités payantes. Aimmy n'est pas, et ne sera jamais, vendu à l'utilisateur final. Il est considéré comme un produit dont le code source est disponible, et non comme un logiciel libre, car nous décourageons fortement les autres développeurs de créer des versions commerciales dérivées d'Aimmy.

Veuillez ne pas confondre Aimmy avec un projet open-source, nous ne le sommes pas et nous ne l'avons jamais été.

Envie de communiquer avec nous ? Rejoignez notre serveur Discord : https://discord.gg/aimmy

Si vous souhaitez partager Aimmy avec vos amis, notre site web est : https://aimmy.dev/

Table des matières
Quel est le but d'Aimmy ?
Comment fonctionne Aimmy ?
Caractéristiques
Installation
En quoi Aimmy est-il meilleur que les outils similaires basés sur l'IA ?
Comment diable Aimmy peut-il être gratuit ?
Comment puis-je entraîner mon propre modèle ?
Comment puis-je télécharger mon modèle dans le menu « Modèles téléchargeables » ?
Quel est le but d'Aimmy ?
Aimmy a été conçu pour les joueurs qui sont fortement désavantagés par rapport aux joueurs normaux.
Cela inclut, sans toutefois s'y limiter :
Les joueurs en situation de handicap physique
Les joueurs qui ont un handicap mental
Les joueurs souffrant de déficiences visuelles non traitées/intraitables
Les joueurs qui n'ont pas accès à un périphérique d'interface homme-machine (HID) séparé pour contrôler le pointeur
Les joueurs qui tentent d'améliorer leur temps de réaction
Les joueurs ayant une mauvaise coordination main-œil
Les joueurs qui obtiennent de mauvais résultats aux jeux FPS
Les joueurs qui jouent pendant de longues périodes dans des environnements chauds ont les mains grasses, ce qui rend la visée difficile.
Comment fonctionne Aimmy ?

Lorsque vous appuyez sur la gâchette, Aimmy capture l'écran et analyse l'image grâce à une intelligence artificielle qui exploite les capacités de votre ordinateur. Le résultat, combiné aux réglages effectués sur les axes X et Y ainsi qu'à votre champ de vision, modifie la position du curseur de votre souris.

Caractéristiques
Interface utilisateur complète
Aimmy propose une interface utilisateur complète et bien conçue pour une utilisation facile et un paramétrage aisé du jeu.
Algorithme de détection par IA DirectML + ONNX + YOLOv8
L'utilisation de ces technologies permet à Aimmy d'être l'un des mécanismes d'alignement de visée les plus précis et les plus rapides au monde.
Système de personnalisation dynamique
Aimmy propose un système de personnalisation interactif doté de nombreuses fonctionnalités qui mettent automatiquement à jour le mode de visée d'Aimmy en fonction de vos réglages. De la confiance de l'IA au champ de vision, Aimmy permet à chacun d'ajuster facilement sa visée.
Système visuel dynamique
Aimmy intègre un système ESP universel qui met en évidence le joueur détecté par l'IA. Ceci est utile aux utilisateurs malvoyants qui ont des difficultés à distinguer les ennemis, ainsi qu'aux créateurs de configurations qui tentent de déboguer leurs créations.
Méthode de déplacement de la souris
Aimmy vous permet de choisir parmi 5 méthodes de mouvement de souris en fonction du type de souris et du jeu pour un meilleur alignement de la visée.
Possibilité de remplacement à chaud
Aimmy vous permet de changer de modèle et de configuration à chaud, même en déplacement. Il n'est pas nécessaire de réinitialiser Aimmy pour appliquer vos modifications.
Magasin de modèles et de configurations avec prise en charge des référentiels
Aimmy facilite l'accès à tous les modèles et configurations dont vous pourriez avoir besoin, et grâce à la prise en charge des dépôts, vous pouvez vous tenir au courant des derniers modèles et configurations de vos créateurs préférés.
Installation
Téléchargez et installez la version x64 de .NET Runtime 8.0.XX
Téléchargez et installez la version x64 de Visual C++ Redistributable.
Téléchargez Aimmy depuis la section Releases (assurez-vous qu'il s'agit du fichier zip d'Aimmy et non du fichier zip source).
Extraire le fichier Aimmy.zip
Exécutez Aimmy.exe
Choisissez votre modèle et profitez-en :)
En quoi Aimmy est-il meilleur que les outils similaires basés sur l'IA ?
Aimmy est développé en C# avec .NET 8 et WPF, et utilise des bibliothèques existantes comme DirectML et ONNX. Cela nous a permis de créer un outil d'alignement de visée très rapide et hautement compatible avec les GPU AMD et NVIDIA, sans compromettre l'expérience utilisateur.

Aperçu de l'interface utilisateur

Au-delà des fonctionnalités de base, Aimmy ajoute également des fonctionnalités supplémentaires exceptionnelles comme la détection ESP pour vous aider à personnaliser votre expérience de jeu selon vos préférences.

Aimmy est livré avec un modèle d'IA bien entraîné et des milliers d'images.

Outre ce modèle, Aimmy propose des dizaines d'autres modèles créés par la communauté via la boutique et notre serveur Discord, et de nouveaux modèles sont développés quotidiennement par d'autres utilisateurs d'Aimmy. Ces modèles varient selon le jeu et le nombre d'images, ce qui rend Aimmy incroyablement polyvalent et universel pour des milliers de jeux actuellement disponibles sur le marché.

Comment diable Aimmy peut-il être gratuit ?
Aimmy, un système d'alignement de visée basé sur l'IA, ne nécessite aucune maintenance car il ne lit aucune donnée de jeu spécifique pour fonctionner. Même si l'équipe d'Aimmy cessait la maintenance du projet, Aimmy continuerait de fonctionner, même sans reprise ni développement.

Cela signifie que, même si nous engageons actuellement des dépenses directes pour faire fonctionner Aimmy, ces dépenses sont suffisamment faibles pour qu'il ne soit pas nécessaire qu'Aimmy fonctionne même avec un modèle financé par la publicité.

Nous ne cherchons pas à gagner de l'argent avec Aimmy, nous recherchons simplement vos gentils mots <3, et une chance d'aider les gens à mieux viser, en les assistant dans leur visée ou même en entraînant leur technique de visée (oui, vous pouvez aussi utiliser Aimmy de cette façon).

Comment puis-je entraîner mon propre modèle ?
Veuillez consulter le tutoriel vidéo ci-dessous pour apprendre à étiqueter des images et à entraîner votre propre modèle. (Redirige vers YouTube) Regardez la vidéo sur YouTube

Comment puis-je télécharger mon modèle dans le menu « Modèles téléchargeables » ?
Veuillez lire le tutoriel dans UploadModel.md
