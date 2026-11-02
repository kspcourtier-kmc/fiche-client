# Fiche client KMC Conseils

Page publique de la fiche client pré-contractuelle de KMC Conseils (courtier en assurances, ORIAS n° 16004050).
Elle ne contient aucune donnée : chaque client y accède par un lien personnel sécurisé.

## Fiche de faisabilité financement (`financement/`)

Variante « passe-plat » (02/11/2026) : le client remplit la fiche en ligne, ses réponses partent par e-mail
directement au partenaire financement de KMC Conseils (ADM Courtage / AVICAP), avec KMC en copie. KMC Conseils
n'en conserve que la trace de transmission. La page construit son formulaire à partir du schéma renvoyé par
l'edge function `fiche-financement` (dépôt HIRAM, `supabase/functions/fiche-financement/champs.ts`) : les
champs se modifient là-bas, jamais ici. Aucune question de santé.
