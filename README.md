# To-Do List — Dashboard de Productivité Excel

Tableau de suivi de tâches hebdomadaire avec **KPIs automatisés** et **barres de progression dynamiques**, entièrement construit sur Excel (formules + mise en forme conditionnelle).

---

## Aperçu

**Indicateurs en temps réel :**

| KPI | Description |
|-----|-------------|
| Total tâches | Nombre total de tâches suivies |
| En attente | Tâches non démarrées |
| En cours | Tâches en progression |
| Terminé | Tâches achevées |
| Progression globale | % moyen calculé automatiquement sur l'ensemble des tâches |

---

## Structure du tableau

| Colonne | Description |
|---------|-------------|
| N° | Identifiant de la tâche |
| Tâche | Intitulé de l'action à réaliser |
| Catégorie | Gestion de projet · Organisation · Finance · Technique · Marketing · Communication · Analyse · Design · Rédaction |
| Priorité | Haute · Moyenne · Basse |
| % | Pourcentage d'avancement (0% à 100%) |
| Progression | Barre de progression visuelle (mise en forme conditionnelle) |
| Notes | Contexte ou prochaine action |
| Situation | En attente · En cours · Terminé |

---

## Fonctionnalités

- **Date du jour** automatique (`AUJOURDHUI()`)
- **Comptage dynamique** des tâches par statut (formules `COUNTIF`)
- **Progression globale** calculée par moyenne pondérée des % individuels
- **Barres de progression** avec mise en forme conditionnelle Excel
- **Catégorisation** par domaine d'activité pour une vue multi-projets

---

## Utilisation

1. Ouvrir `To-Do-List.xlsx` dans Excel ou Google Sheets
2. Ajouter une ligne par nouvelle tâche dans le tableau
3. Renseigner catégorie, priorité et % d'avancement
4. Les KPIs en haut du tableau se mettent à jour automatiquement

---

## Stack technique

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

---

## Auteur

**Emmanuel KOURAOGO**
[GitHub](https://github.com/EKOURAOGO) · [Email](mailto:ekouraogo73@gmail.com)
