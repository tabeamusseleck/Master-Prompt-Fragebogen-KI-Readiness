PROMPT-START: GENERIERUNG EINES THEORIEGELEITETEN FRAGEBOGENS ZUR KI-READINESS

Rolle & Zielsetzung:
Du agierst als führender Experte für Wirtschaftsinformatik, Organisationspsychologie und empirische Sozialforschung. Deine Aufgabe ist es, einen wissenschaftlich fundierten, theoriegeleiteten Fragebogen zur Messung der KI-Readiness (KI-Bereitschaft) in Unternehmen vor der Implementierung von Künstlicher Intelligenz zu erstellen.

Theoretisches Fundament (Zwingende Inhaltsfilter):
Der Fragebogen MUSS die folgenden drei Theorien zwingend als inhaltliche Filter für die Fragengenerierung nutzen. Jedes Item muss sich eindeutig auf mindestens eines dieser Theoriekonstrukte stützen:

1. Reasoned Action Approach (RAA):
   Operationalisierung individueller psychologischer Faktoren der Mitarbeiter und Führungskräfte:
   - Einstellung (Attitude): Bewertung der KI-Nutzung als vorteilhaft, zufriedenstellend oder wichtig.
   - Wahrgenommene Normen (Perceived Norms / Social Influence): Wahrgenommener sozialer Druck und Empfehlungen durch relevante Dritte (Kollegen, Führungskräfte, Peer-Groups).
   - Wahrgenommene Verhaltenskontrolle (Perceived Behavioral Control / Self-Efficacy): Empfundene Eigenkontrolle, Handlungsfreiheit und persönliche Fähigkeiten zur Nutzung der KI.

2. Behavioral Theory of the Firm (BTF):
   Erfassung organisatorischer Verhaltensweisen und Entscheidungsmechanismen:
   - Organisatorische Routinen & Barrieren: Bestehende Arbeitsabläufe, Schnittstellenprobleme und Feststecken in experimentellen Pilotprojekten (Proofs of Concept).
   - Unsicherheitsvermeidung (Uncertainty Avoidance): Risikoscheues Verhalten, Bevorzugung kurzfristig organisierbarer Reaktionen und Festhalten am Status quo.
   - Sufficing / Lokale Suche: Ausrichtung auf „ausreichende“ statt optimale Lösungen unter Informationsasymmetrien.
   - Zielkonflikte & Koalitionen (Quasi-Resolution of Conflict): Divergierende Zielsetzungen zwischen verschiedenen Stakeholdern und Fachbereichen (z. B. IT vs. Fachabteilungen).

3. Dynamic Capabilities View (DCV):
   Messung der organisatorischen Fähigkeiten zur Umgestaltung von Ressourcen:
   - Sensing (Erkennung): Fähigkeit der Unternehmung, technologische Potenziale, KI-Trends und Marktchancen frühzeitig zu identifizieren.
   - Seizing (Mobilisierung): Fähigkeit, KI-Strategien, Governance-Strukturen, Geschäftsmodelle und Investitionen zu mobilisieren.
   - Transforming / Orchestrating (Orchestrierung): Fähigkeit zur kontinuierlichen Reorganisation von Ressourcen, IT-Infrastrukturen, Datenarchitekturen und Humankapital (Schulungen/Kompetenzaufbau).

Design Science Research (DSR) – Vier Kern-Dimensionen:
Bei der Generierung der Items musst du folgende vier Dimensionen strikt berücksichtigen:
1. Akteursdifferenzierung: Der Fragebogen MUSS in zwei getrennte Zielgruppen-Abschnitte unterteilt sein:
   a) Management / Führungskräfte (Fokus auf Strategie, Governance, Ressourcen, organisatorische Barrieren, DCV und BTF).
   b) Operative Mitarbeiter / Anwender (Fokus auf Alltagstauglichkeit, Akzeptanz, individuelle Verhaltenskontrolle, Bedenken, RAA).
2. Funktionale Anforderungen:
   - Generiere je Theoriekonstrukt maximal 5 Items (um Überlänge zu vermeiden).
   - Jedes Item muss klar formuliert, eindeutig skalierbar und inhaltlich valide sein.
3. Qualitative Gütekriterien:
   - Skalierung: Nutze für ALLE Items ausnahmslos eine 7-stufige Likert-Skala (1 = „Trifft überhaupt nicht zu“ bis 7 = „Trifft voll und ganz zu“).
   - Trennschärfe & Objektivität: Keine mehrdeutigen, verschachtelten oder unklaren Formulierungen.
   - Vermeidung von Suggestivfragen: Alle Aussagen müssen sachlich und wertneutral formuliert sein.
4. Umwelt- und Kontextfaktoren (Dynamische Variablen):
   - Der Fragebogen muss universell anwendbar, aber branchenspezifisch anpassbar sein.
   - Baue dazu in die Item-Formulierungen explizit die Platzhalter-Variablen `[Branche]`, `[KI-Anwendung]` und `[Ziel-Prozess]` ein (z. B. „In unserer Arbeit in der [Branche]...“ oder „Durch den Einsatz von [KI-Anwendung] in Bereich [Ziel-Prozess]...“).

Ausgabeformat:
Gib das Ergebnis ausschließlich in deutscher Sprache und als strukturierte Markdown-Tabelle aus.
Die Tabelle MUSS folgende Spalten enthalten:

| Zielgruppe | Theorie & Konstrukt | Item-ID | Item-Formulierung (mit Variablen) | Antwortskala | Inhaltliche Begründung / DSR-Kontext |
|---|---|---|---|---|---|

Beachte bei den Spalten:
- Zielgruppe: [Management] oder [Operative Mitarbeiter]
- Theorie & Konstrukt: Diskrete Kennzeichnung der Zuordnung (z. B. "RAA – Attitude", "BTF – Uncertainty Avoidance", "DCV – Sensing")
- Item-ID: Eindeutiges Kürzel (z. B. M-RAA-01, E-BTF-02)
- Item-Formulierung: Konkreter Item-Text mit Variablen wie `[Branche]` oder `[KI-Anwendung]`
- Antwortskala: „7-stufige Likert-Skala (1–7)“
- Inhaltliche Begründung: Kurze Erklärung, welches organisatorische oder psychologische Phänomen das Item misst.

Erstelle nun den vollständigen Fragebogen nach diesen Vorgaben.
PROMPT-ENDE


Anwendung des Master-Prompts
Wenn Sie diesen Master-Prompt in ein LLM eingeben, steuert er das Modell so, dass es:
Keine externen oder erfundenen Theorien verwendet, sondern exakt bei der Triade aus RAA
, BTF
 und DCV
 bleibt.
Die Perspektiven trennt, sodass Sie direkt vergleichende Messungen zwischen Führungsebene und Belegschaft durchführen können
.
Praktisch einsetzbar ist, da durch die Variablen [Branche] (z. B. Gesundheitswesen, Fertigung) und [KI-Anwendung] (z. B. Generative KI / LLMs, Bilderkennung) der Fragebogen sofort an Ihr konkretes Forschungsumfeld angepasst werden kann.
Möchten Sie, dass wir diesen Master-Prompt anhand eines konkreten Szenarios (z. B. Einsatz von LLMs im Gesundheitswesen) testweise ausführen, um das Ergebnis gemeinsam zu evaluieren?

*ERGÄNZUNG*
Ich habe noch eine Ergänzung. Behalte das Ausgabeformat bei inklusive aller genannten Spalten. ergänze aber zudem eine weitere Tabelle, nur mit Item-ID, Item-Formulierung und Antwortskala.Bitte getrennt nach Zielgruppe. Diese weitere Tabelle soll den fertigen Fragebogen für die Probanden darstellen. Wenn keine Rückfragen mehr bestehen, führe den Prompt testweise für die Versicherungsbranche aus.
