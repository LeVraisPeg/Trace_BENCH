

### 1️⃣ Notebook principal (Google Colab)

**`PEGLIASCO_OpenTrace_BENCH_GSM8k_BBEH_LangGraph_Trace.ipynb`**

Ce notebook contient :

- La définition des **stratégies LangGraph** :
  - `solve_with_PAL_Strategy`
  - `solve_with_verification`
  - (et autres stratégies explorées)
- Les **fonctions de benchmark BBEH**
- Les **runners Legacy et New Bench**
- Les **cellules correspondant à la TASK 2**

👉 **Les cellules de la TASK 2 se trouvent dans le notebook sous les titres :**

- `Task 2 — New bench (MinibatchAccumulationAlgorithm)`
- `Task 2 — New bench (MinibatchAccumulationAlgorithm) RESUMABLE`

Ces cellules :
- utilisent `accumulation_steps` à la place de `batch_size`
- comparent plusieurs tâches BBEH
- testent plusieurs stratégies
- assurent une exécution **reproductible et relançable**

---

### 2️⃣ Résumé des résultats (léger)

**`results_summary.jsonl`**

Ce fichier contient un **résumé léger et exploitable** des expériences de la TASK 2.

Chaque ligne correspond à **un run** et inclut notamment :

- `task_name`
- `strategy`
- `accumulation_steps`
- `baseline_acc`
- `final_val_acc`
- le chemin vers le `best_state.txt` correspondant

👉 Ce fichier est volontairement conservé dans GitHub car :
- il est léger
- il permet d’analyser/comparer les résultats sans relancer les benchmarks
- il ne contient ni données sensibles ni fichiers volumineux

---

## 📁 Résultats complets (Google Drive)

Les **résultats complets** (logs détaillés, états intermédiaires, best states, historiques)
ne sont **pas stockés sur GitHub**, pour des raisons de taille et de stabilité.

Ils sont disponibles sur **Google Drive** :

📎 **Lien Google Drive (lecture seule)**  
👉 https://drive.google.com/drive/folders/1WzsCaKWLjUrDzQTYqFVmjwvYP4oTP_QD?usp=drive_link




