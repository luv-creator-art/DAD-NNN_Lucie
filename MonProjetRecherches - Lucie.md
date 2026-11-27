# Projet Nouvelles Narrations Numériques

## Gribouillis

### 27/11/2026

Je commece par me renseigner sur les GAN en suivant la vidéo 
Pour expliquer ce que c'est : https://www.tensorflow.org/tutorials/generative/dcgan?hl=fr

--> Les réseaux antagonistes génératifs (GAN) sont deux modèles sont formés simultanément par un processus contradictoire. Un générateur ("l'artiste") apprend à créer des images qui semblent réelles, tandis qu'un discriminateur ("le critique d'art") apprend à distinguer les vraies images des fausses.
Au cours de l'entraînement, le générateur s'améliore progressivement pour créer des images qui semblent réelles, tandis que le discriminateur s'améliore pour les différencier. Le processus atteint l'équilibre lorsque le discriminateur ne peut plus distinguer les images réelles des fausses.

J'ai dans le terminal de vscode installé Python et Git, puis j'ai récupéré le code du tutoriel (DCGAN-Pytorch d'ExplainingAI) dans son github à lui: https://github.com/explainingai-code/DCGAN-Pytorch/tree/main 

et je l'ai mis dans mon dossier GitHub. J'ai préparé un environnement (un dossier .venv) pour que tout ce que j'installe reste dans cette boite et installé PyTorch qui est un outil qui sert à entraîner et fabriquer mon IA (Outil crée par metaIA) pour m'eviter de faire les calculs moi meme . 

![Logo Markdown](img/27Nov_terminalGAN_1.png)
![Logo Markdown](img/27Nov_terminalGAN_2.png)
![Logo Markdown](img/27Nov_terminalGAN_3.png)

ma prochaine étape est d'adapter le code de la vidéo pour lire mes propres images au lieu des chiffres et lancer le premier entraînement. Je pourrai ensuite comparer les gribouillis inventés par mon IA avec ceux de ChatGPT, Copilot, Gemini et Meta AI, et avec les vrais

J'ai également complété ma base de données avec de nouveaux gribouillages j'en ai récolté 40 en gardant la même méthode du bonneteau. 
![Logo Markdown](img/27Nov_chaeryoung_gribouillis.jpg)
![Logo Markdown](img/27Nov_margot_gribouillis.jpg)
![Logo Markdown](img/27Nov_seryoung_gribouillis.jpg)
![Logo Markdown](img/27Nov_sonia_gribouillis.jpg)

### 25/11/2026

tester si une ia ça gribouille : J'ai testé avec 
prompt : Génère une image d'un gribouillis au stylo noir sur fond blanc.   un autre x en boucle 
sur chatgpt, copilot, gemini, meta ia 

![Logo Markdown](img/chatgpt_gribouillis.jpg)
chatgpt
![Logo Markdown](img/copilot_gribouillis.jpg)
copilot

Les deux ia chatgpt et Copilot Fond blanc pur, trait d'une épaisseur régulière, sans aucune variation de pression. Ce sont surtout de grandes boucles ovales et horizontales, qui s'emmêlent au centre et finissent par une petite « queue ». dessin pas realiste comme à l'ordinateur 

![Logo Markdown](img/gemini_gribouillis.jpg)
gemini
Papier realiste avec des plis et du grain, style encre de stylo bille, trait qui s'épaissit et s'éclaircit, sorte de symetrie et le stylo se lève. dessin réaliste, mais plus chargé. 
![Logo Markdown](img/metaia_gribouillis.jpg)
meta ia
comme gemini (traits séparés, pression variable, grain du papier), mais très chargé, gribouilli differents à chaque fois, certaines images ajoutent des symboles reconnaissables comme un cœur, une maison ou une étoile.

entrainer sur ma base 
je pense entrainer 
quel modele? quel data set? tag annoter avec des concepts comment j'annote 

après renseignement j'aimerais entrainer une ia qui part de 0 et uniquement avec mes images, pas partir d'une qui est deja entrainée et l'afffiner. 
Pour cela j'ai trouvé un lien d'un tutoriel pour un DCGAN (Deep Convolutional Generative Adversarial Network) <https://youtu.be/672YP9k6Xws> je commence à me renseigner 

Pour une potentielle V2 :Je viens de penser que je gribouille moins depuis que j'ai un ordi en classe. en revanche meme si je ne fais rien de particulier ma souris passe son temps à bouger sur l'ecran, un gribouillage virtuel ? mon but serait alors de recolter les gribouillis virtuels en faisant un programme qui dessine le mouvement de la souris ? 

### 24/11/2026

**Ce que j'ai fait-->** Première récolte de gribouillis en classe. J'ai voulu mettre en place un dispositif simple me permettant de commencer rapidement à établir une base. Un·e camarade joue au bonneteau (jeu des gobeet /balle) pendant qu'il ou elle trace en continu sur une feuille, sans lever le stylo pendant 10 manches avec une difficulté croissante (vitesse). 

**Observations :** Le jeu influence fortement le trait les joueur·euse·s reproduisent le mouvement de la balle et des gobelets avec leur main. Le tracé est guidé par ce que l'œil suit et surtout comme aide pour trouver la balle. Je garde cette série comme un premier test

L'activité est trop présente visuellement, trop difficile et trop courte. Il faudrait une activité plus passive et plus longue qui occupe l'attention sans imposer un mouvement.

**Prochaine étape :** Tester d'autres activités 
Comparer les séries entre elles.

![Logo Markdown](img/24Nov_1.jpeg)
![Logo Markdown](img/24Nov_nolan_gribouillis.jpg)
![Logo Markdown](img/24Nov_thalie_gribouillis.jpg)
![Logo Markdown](img/24Nov_robin_gribouillis.jpg)

### 23/11
-Def Gribouillis synonyme Sténographie Écriture asémique Gribouillage Graphe Griffonner 
CNRT

-Site qui récolte —> Cours Théorie des médias Étudiants machine Learning caché sous forme de jeu ?
Ex: Captcha, quick draw google
——> RECOLTE RADICALE 

système de récolte simple pour tous : ?  
sujet qu'est ce que je dis
data set interressant par la quantité gribouilli **pratique commune **

Lora 

Reconnaitre forme IA et écriture => faible 

On en fait quoi après ? 
Enjeux ? 

1. Objet que je récolte, trouver les définitions connu, et ma def
2. Qui en a parlé, ce qui existe et a été fait 
3. Récolter, journal de bord, annoter les récoltes jours dates…
4. Classification, reconnaissance ranger
5. On en fait quoi ?
Objet ? Machine à gribouiller ? 

ATTENTION : notion de code basique à incorporer 

Pour le moment ref qu’on m’a donné, élément que je dois consulter ou ref liées 
- Cours théorie des médias
- Vera Molnar Écriture 
- Claude Closky
- Evan Roth Graffiti 
- Neurones et intelligence simulées E+K
- An anthology of Asemic Handwriting Tim Gaze et Michael Jacobson
- Du gribouillis au dessin 
- Machine à dessiner Jean Tinguely 

Prendre position par rapport au ref comment elles ont impacté mon travail 
