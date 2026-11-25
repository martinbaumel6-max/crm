# Mini CRM (100 % local)

Un mini CRM en **un seul fichier HTML**, sans serveur, sans installation, sans internet.

## Utilisation

1. Double-clique sur `crm.html` (ouvre-le dans Chrome, Firefox ou Edge).
2. C'est tout. Les données sont enregistrées automatiquement dans le navigateur (localStorage).

⚠️ Les données sont liées au navigateur **et au fichier/chemin utilisé**. Si tu ouvres le fichier
depuis un autre navigateur ou un autre emplacement, elles n'apparaîtront pas.

## Fonctionnalités

- **Tableau de bord** : contacts, clients, tâches ouvertes, retards, échéances du jour, tâches à venir, dernières activités.
- **Contacts** : nom, entreprise, fonction, email, téléphone, statut (Prospect / Client / Inactif), notes, recherche et filtre, fiche détaillée avec tâches et historique.
- **Tâches** : intitulé, contact lié, échéance, priorité (Basse / Moyenne / Haute), statut (À faire / En cours / Terminée), badge de notification des retards, filtre et recherche.
- **Activités** : journal des échanges (Appel, Email, Réunion, Note) rattachés à un contact.
- **Sauvegarde** : boutons *Exporter* / *Importer* au format JSON (à faire régulièrement, le localStorage n'est pas une sauvegarde à long terme).

## Conseils

- Épingle le fichier dans un dossier stable et mets un raccourci sur le bureau.
- Exporte une sauvegarde JSON de temps en temps : elle te permettra de restaurer tes données
  via le bouton *Importer* (ou de changer de machine).
