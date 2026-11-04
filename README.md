# Registre des opérations maraîchères

> Projet individuel du SAS DFS, brief 1 (sujet : [SUJET.md](SUJET.md)). Remplacez chaque ✏️ par votre texte, puis supprimez cette ligne.

## Contexte

Cet outil est utilisé par un maraîcher pour enregistrer les opérations réalisées sur ses parcelles de culture. Il lui permet de conserver un historique des travaux effectués et des coûts associés. L'utilisateur saisit un identifiant, une date, une parcelle, une culture, un type d'opération et un coût. Le programme enregistre ces informations et peut afficher la liste des opérations enregistrées. Il aide à suivre les dépenses liées aux cultures. En revanche, il ne gère pas les ventes des récoltes ni les revenus. Il ne permet donc pas de calculer la rentabilité de l'exploitation.

## Prérequis et lancement

- Node.js 20 ou plus récent, Git ; aucune bibliothèque à installer.

```bash
git clone https://github.com/VOTRE-COMPTE/brief-1-registre-maraicher.git
cd brief-1-registre-maraicher
node app.js
npm test
```

Sous PowerShell, si `npm` est bloqué : `npm.cmd test`.

## Fonctionnalités

✏️ *Cochez seulement ce qui marche : `- [x]`.*

- [x] Données lues et enregistrées dans `donnees/operations.json`
- [x] Ajouter une opération, saisies invalides refusées sans arrêter le programme
- [x] Lister les opérations, message si le registre est vide
- [x] Rechercher par identifiant ou par parcelle ; filtrer par culture
- [x] Trier par coût ou par date
- [ ] Synthèse : total, nombre et total par parcelle, coût minimum et maximum
- [ ] Bonus : supprimer et modifier une opération (choix 6 et 7)
- [ ] Bonus : tri par coût décroissant, parcelle la plus coûteuse

## Données

✏️ *Le fichier, le nombre d'opérations, les champs (voir [docs/dictionnaire-donnees.md](docs/dictionnaire-donnees.md)), les unités. Rappelez qu'elles sont fictives.*

## Limites

Le registre enregistre uniquement les dépenses et non les revenus.
Il ne permet donc pas de calculer la rentabilité d'une culture.
Les stocks de recoltes ne sont pas enregistrés
Les informations météorologiques et hygrometriques ne sont pas prises en compte
## Documents

[Dictionnaire des données](docs/dictionnaire-donnees.md) · [Tâches](docs/taches.md) · [Relevé des tests](docs/releve-tests.md) · [Journal de recherche](docs/journal-recherche.md) · [Fiche agronomique](docs/fiche-agronomique.md) · [Fiche individuelle](docs/fiche-individuelle.md)

## Auteur

Kakeu Zran Bruce, compte GitHub. Entraide : avec qui, sur quoi.*
