# 📄 README : Tableau de Bord d'Absentéisme

## Introduction

Ce projet contient le script Python (**stp_6_dash.py**) permettant de générer une analyse complète du taux d'absentéisme sous forme de tableau de bord (dashboard) regroupant quatre visualisations clés.

-----

## 🚀 Exécution du Code

Pour exécuter le script et afficher le tableau de bord :

1.  **Vérification du chemin d'accès :** Ouvrez le fichier Python et assurez-vous que la variable `DATA_FILE_PATH` dans le bloc `if __name__ == "__main__":` pointe vers l'emplacement exact de votre fichier `taux_absenteisme_data.xlsx`.
2.  **Exécution :** Lancez le script depuis votre terminal ou environnement de développement :
    ```bash
    python votre_script_name.py
    ```
3.  Le tableau de bord combiné (4 graphiques en 2x2) s'affichera dans une fenêtre Matplotlib pop-up.

-----

## 🛠️ Dépendances

Ce script nécessite les librairies Python suivantes. Elles peuvent être installées via `pip` :

```bash
pip install pandas matplotlib seaborn openpyxl
```

-----

## 📂 Structure des Fichiers

| Chemin | Description |
| :--- | :--- |
| `tp_6_dash.py` | Le script principal contenant les fonctions de calcul et de visualisation. |
| `data/taux_absenteisme_data.xlsx` | **Source de données obligatoire** contenant les colonnes de jours d'absence et jours travaillables. |

-----

## 🎯 Périmètre de la Maquette

Le script produit un tableau de bord analytique couvrant :

1.  Le **Taux d'absentéisme par catégorie** (Barres horizontales).
2.  Le **Taux d'absentéisme par mois** (Ligne de tendance).
3.  La **Répartition des jours d'absence** (Diagramme en Donut).
4.  L'**Absentéisme par Mois et Catégorie** (Carte de chaleur / Heatmap).

**Sortie :** Le script affiche le tableau de bord combiné à l'écran (`plt.show()`).
