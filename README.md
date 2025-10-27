Témoignages Codeloccol
Description

Ce projet est une page web présentant des cartes de témoignages pour les étudiants de Codeloccol. Chaque carte affiche :

Le design est moderne, responsive et utilise des dégradés sur certaines bordures.

Commandes CSS importantes utilisées et leur rôle
Propriété / Commande	Utilité dans le projet
display: flex;	Permet d’aligner les éléments horizontalement ou verticalement, utilisé pour les avatars, noms et étoiles.
justify-content: space-between;	Espace uniformément les éléments dans un conteneur flex.
align-items: center;	Centre les éléments sur l’axe vertical dans un conteneur flex.
gap: 10px;	Définit l’espacement entre les éléments dans un flex ou grid.
flex: 1 1 auto;	Permet aux cartes de grandir ou rétrécir selon l’espace disponible, utilisé pour le responsive.
max-width: 100%;	Empêche les cartes de dépasser leur conteneur.
border-radius: 10px;	Arrondit les coins des cartes pour un rendu esthétique.
box-shadow: 0 4px 8px rgba(0,0,0,0.1);	Ajoute une ombre douce autour de la carte pour un effet flottant.
transition: transform 0.3s ease, box-shadow 0.3s ease;	Anime les cartes au survol (hover) pour un effet dynamique.
:hover { transform: translateY(-5px); }	Décale légèrement la carte vers le haut lors du survol.
background: linear-gradient(...);	Crée des dégradés de couleur pour le fond ou les bordures.
border-image: linear-gradient(...) 1;	Applique un dégradé uniquement sur les bordures de la carte.
@media screen and (max-width: 768px) { ... }	Définit des styles spécifiques pour les tablettes et mobiles (responsive).
padding: 0.9rem;	Ajoute de l’espace à l’intérieur des cartes pour éviter que le texte touche les bords.
font-family: 'Poppins', sans-serif;	Définit la police principale du site pour un style moderne.
