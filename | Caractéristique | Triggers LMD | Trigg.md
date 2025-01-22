| Caractéristique        | Triggers LMD                        | Triggers LDD                          |
|------------------------|-------------------------------------|---------------------------------------|
| **Activé par**         | Opérations sur les **données** : `INSERT`, `UPDATE`, `DELETE`. | Opérations sur la **structure** : `CREATE`, `ALTER`, `DROP`. |
| **Portée**             | Agit sur des **lignes** ou des **instructions**. | Agit sur un **schéma** ou sur la **base de données** entière. |
| **Exemples d'usage**   | - Vérifications métier<br>- Journalisation des modifications de données<br>- Automatisation des calculs. | - Empêcher certaines modifications au niveau du schéma<br>- Journalisation des modifications d'objets. |
| **Exécution fréquente**| Plus fréquents, car ils réagissent aux modifications des données. | Plus rares, car ils réagissent aux modifications du schéma. |
