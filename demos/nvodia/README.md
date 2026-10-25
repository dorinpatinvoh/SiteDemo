# Quatre démos NVODIA

HTML, CSS et JavaScript sans dépendances ni compilation. Ouvrir index.html ou les quatre pages directement. Les images JPEG sont dans images/.

- boutique.html : catalogue avec filtres et demande (taille/couleur).
- patisserie.html : modèles et demande (date/parts).
- immobilier.html : biens fictifs et demande de visite.
- beaute.html : prestations et demande de rendez-vous.

## WhatsApp
Dans chaque HTML, renseigner WHATSAPP_NUMBER avec le numéro validé du professionnel au format international, chiffres uniquement. Aucun numéro configuré par défaut. Après préparation du message, le bouton apparaît et ouvre un brouillon WhatsApp ; l'utilisateur décide d'envoyer. Le bouton Copier dépend des permissions du navigateur, avec sélection manuelle du texte en secours. Aucun stockage ni paiement.

## Personnalisation
Couleurs dans :root ; fiches dans DATA.items ; image dans .hero-img img. Les quatre fiches d'un secteur partagent une image d'ambiance illustrative. Les remplacer par des photos propres à chaque fiche pour un usage réel. Marques, prix, biens, coordonnées de biens et durées fictifs. Ne pas présenter ces démos comme des références clients. Les prompts des quatre images IA sont dans PROMPTS_IMAGES.json.

## Déploiement
Les liens depuis l'accueil et realisations.html pointent vers ce dossier. Déploiement statique depuis la racine existante du dépôt ; aucune nouvelle configuration Netlify nécessaire. Parcours : accueil → sélection → fiche → formulaire → message préparé.
