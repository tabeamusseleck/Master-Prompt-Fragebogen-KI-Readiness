# LLM-Master-Prompt zur automatisierten Generierung theoriegeleiteter Fragebögen zur Messung der KI-Readiness in Unternehmen

Dieses Repository enthält das im Rahmen des Moduls Praxisseminar entwickelte Artefakt: einen **LLM-Master-Prompt**, der in Kombination mit Google NotebookLM eingesetzt wird, um wissenschaftlich fundierte und praxisnahe Fragebögen zur Messung der „KI Readiness“ in Unternehmen zu generieren.

---

## 📂 Struktur des Repositories
- `/prompts/` -> Enthält die verschiedenen Versionen des Master-Prompts (von v1.0 bis zur finalen Version).
- `/evaluations/` -> Dokumentation der Testläufe und Evaluationsergebnisse.
- `README.md` -> Projektdokumentation (diese Datei).

---

## 🧠 Theoretisches Fundament des Prompts
Der Master-Prompt übersetzt etablierte verhaltens- und managementwissenschaftliche Theorien in konkrete Frage-Items:
1. **Reasoned Action Approach (RAA)** (Fishbein & Ajzen, 2010) – Individuelle Einstellungen und Verhaltenskontrolle.
2. **Behavioral Theory of the Firm (BTF)** (Cyert & March, 1963) – Organisatorische Routinen und Risikoscheu.
3. **Dynamic Capabilities View (DCV)** (Teece, 2007) – Ressourcenorchestrierung und Transformation.

---

## 🚀 Anwendung in Google NotebookLM
1. Ein neues Notebook in Google NotebookLM erstellen
2. Hochladen der vorgegebenen und weiterer Quellen (Fragebögen, Fachliteratur zu KI-Readiness,...)
3. Kopieren des Auftrags-Prompts (Meta-Prompt) (aus dem Ordner `/prompts/`) in den Chat von NotebookLM.
4. Den von NotebookLM erstellten ersten Entwurf des Master-Prompts prüfen und kleine Anpassungen vornehmen
5. Prompt wird ausgeführt, um den ersten strukturierten Fragebogen zu generieren.
6. Verfeinerung des Prompts mittels iterativen Prozess
