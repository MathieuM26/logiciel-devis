# Logiciel de devis — M26 INFORMATIQUE

Générateur de devis pour **M26 INFORMATIQUE**, entreprise de montage PC sur mesure (Belgique).

## 👉 Application en ligne

**https://mathieum26.github.io/logiciel-devis/**

Aucune installation : tout fonctionne directement dans le navigateur (PC et mobile).

## Fonctionnalités

- **Configurations PC pré-montées** : Starter (999 €), Apex (1999 €), Titan (3599 €) — montage inclus.
- **Service de montage seul** à 100 € (le client apporte ses propres composants).
- **Infos client** et **lignes personnalisées** (composant supplémentaire, remise…).
- **Calcul automatique** : sous-total HTVA, TVA belge 21 %, total TTC (prix saisis en TTC).
- **En-tête entreprise** (dénomination, adresse, n° BCE, n° TVA, IBAN) mémorisé sur l'appareil.
- **Génération du devis** : numéro automatique, date, validité 30 jours, conditions, impression / export PDF.

## Conditions par défaut

- Devis valable 30 jours
- Garantie pièces et main d'œuvre 2 ans
- Délai de montage 5 à 15 jours ouvrés (stress test 24h inclus)
- Paiement de la totalité à la commande

## Utilisation

1. Ouvrir l'application via le lien ci-dessus.
2. Remplir une fois la section **Mon entreprise**, puis cliquer sur *Enregistrer mes infos*.
3. Sélectionner les configs / services et renseigner le client.
4. Cliquer sur **Générer / imprimer le devis**, puis enregistrer en PDF.
   *(Astuce : dans la fenêtre d'impression, décocher « En-têtes et pieds de page » pour un PDF sans URL ni titre du navigateur.)*

## Technique

Page web autonome (`index.html`) — HTML, Tailwind CSS (CDN) et icônes Lucide. Hébergée gratuitement via GitHub Pages.
