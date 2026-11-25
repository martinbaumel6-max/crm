# NutriRuminant CRM (100 % local)

CRM Commercial B2B en **un seul fichier HTML**, sans serveur ni installation — toutes les
librairies (Tailwind CSS, Chart.js, icônes Lucide, lecteur Excel SheetJS) sont **embarquées dans
le fichier** : il fonctionne **100 % hors ligne**, sans aucune connexion internet. Les données
sont chiffrées et enregistrées dans le navigateur.

## Fichiers

| Fichier | Description |
|---|---|
| `nutriruminant-crm.html` | CRM complet : comptes clients, catalogue & gammes, ventes par année, pipeline d'opportunités, tâches Kanban, RDV & comptes-rendus de visites, import/export CSV-Excel-JSON, verrouillage par mot de passe (chiffrement AES-GCM) |
| `crm.html` | Mini CRM générique plus simple (contacts / tâches / activités) |

## Utilisation

1. Télécharge le fichier choisi et double-clique dessus (Chrome, Firefox ou Edge récents).
2. À la première ouverture, crée ton mot de passe : **il ne peut pas être récupéré** (les données
   sont chiffrées avec). Fais régulièrement une sauvegarde JSON (onglet Import / Export).
3. Les données restent dans ce navigateur sur cet ordinateur ; la sauvegarde JSON permet de les
   transférer ou de les restaurer.

## Fonctionnalités clés (nutriruminant-crm.html)

- **Tableau de bord** avec sélecteur d'année : volumes vendus, pipeline en cours, RDV à venir, top clients, graphiques par gamme et par région
- **Comptes clients B2B** : typologie (fabricant / distributeur), statut commercial (prospect / actif / dormant), potentiel annuel et taux de pénétration, parties prenantes, notes
- **Ventes par année** : volumes par produit et par année (saisie manuelle ou import), détail par année sur la fiche client
- **Pipeline d'opportunités** : Kanban À ouvrir → 1er contact → Offre envoyée → Négociation → Gagnée / Perdue, avec potentiel tonnage et prochaine action
- **Suivi terrain** : agenda des RDV planifiés (avec alerte « à reporter »), comptes-rendus de visites, conversion d'un RDV en compte-rendu en un clic
- **Tâches** : Kanban à 4 colonnes avec priorités, échéances, tri et drag & drop
- **Import / Export** : CSV & Excel avec aperçu avant confirmation (colonnes détectées automatiquement, incl. colonne `Année`), export CSV des ventes, sauvegarde / restauration JSON

⚠️ Les données sont liées au navigateur **et au fichier/chemin utilisé**. Si tu ouvres le fichier
depuis un autre navigateur ou un autre emplacement, elles n'apparaîtront pas (serialize une
sauvegarde JSON pour migrer).

✅ **Aucune connexion internet requise** : le fichier est totalement autonome (librairies
v3.4.16 / Chart.js 4.4.7 / Lucide 0.468.0 / SheetJS 0.18.5 embarquées, ~1,6 Mo). Tu peux le
copier sur une clé USB, l'envoyer par mail ou l'utiliser en avion.
