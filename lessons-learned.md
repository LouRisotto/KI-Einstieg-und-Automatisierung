# 💡 Lessons Learned – Meine Erfahrungen mit GitHub Copilot

Dieses Dokument fasst meine wichtigsten Erkenntnisse aus der täglichen Arbeit mit **GitHub Copilot**, **Visual Studio** und verschiedenen Automatisierungsprojekten zusammen.  
Es soll Kolleginnen und Kollegen helfen, Copilot realistisch einzuschätzen und produktiv einzusetzen.

---

# 🚀 1. Copilot ist ein starkes Werkzeug – aber kein Autopilot

Copilot kann:

- Codeblöcke schnell vervollständigen  
- Standardlogik effizient generieren  
- Vorschläge machen, die als Inspiration dienen  
- repetitive Aufgaben beschleunigen  

Aber:

- Copilot **versteht nicht immer den Kontext**  
- fachliche Regeln (z. B. aus BIM, DWG, LISP) sind ihm oft unbekannt  
- komplexe logische Abläufe werden häufig falsch oder unvollständig erzeugt  

**Fazit:**  
Copilot hilft viel – aber nur, wenn man prüft, verbessert und korrigiert.

---

# 🧠 2. Gute Prompts = gute Ergebnisse

Je klarer ich formuliere:

- *was* ich möchte,  
- *warum* ich es brauche,  
- *in welchem Kontext* es genutzt wird,

desto besser funktioniert Copilot.

### Gute Beispiele:
- „Erstelle eine Funktion, die PDF‑Seiten via OCR ausliest und anhand des BIM‑Codes benennt.“  
- „Gib mir eine LISP‑Schleife, die alle Layouts durchgeht und das Datum aktualisiert.“

### Schlechte Beispiele:
- „Schreib mir was für PDFs.“  
- „Mach die DWG‑Z‑Werte.“

**Fazit:**  
Copilot ist umso hilfreicher, je genauer ich meine Anforderungen kenne.

---

# 🐞 3. Fehler von Copilot sind Lernchancen

Copilot macht oft typische Fehler:

- erfindet Funktionen, die nicht existieren („Halluzinationen“)  
- verwechselt Dateistrukturen oder Datentypen  
- schlägt unvollständigen Code vor  
- macht syntaktische Fehler in LISP  
- interpretiert DWG‑Logik falsch  

Diese Fehler helfen mir zu erkennen:

- wie gut ich selbst die Logik verstehe  
- wo ich Anforderungen klarer formulieren muss  
- welche Teile eines Problems KI‑ungeeignet sind  

**Fazit:**  
Fehler = wertvolle Lernmomente.

---

# 🔧 4. Copilot ersetzt kein Fachwissen

Besonders deutlich wird das bei:

- BIM‑Codierung  
- AutoCAD‑Datenanalyse (DWG / Z‑Koordinaten)  
- LISP‑Automatisierung  
- internen AFRY‑Skripten & Abläufen  
- eigenen Projektstrukturen  

Hier kann Copilot unterstützen, aber nicht entscheiden.

**Fazit:**  
Ich muss immer Fachentscheidung treffen – Copilot liefert nur Vorschläge.

---

# 🧩 5. Copilot ist am stärksten bei kleinen Bausteinen

Typische Aufgaben, bei denen Copilot glänzt:

- Schleifen  
- Datenumwandlungen  
- Regex‑Vorschläge  
- Helferfunktionen  
- kleine Python‑Skripte  
- Code‑Refactoring  
- Erklärungen / Kommentare generieren  

**Fazit:**  
Je kleiner und klarer der Codeblock, desto besser Copilot.

---

# ⚙️ 6. Copilot schwächelt bei komplexen Arbeitsprozessen

Besonders schwierig für Copilot:

- Multi‑Step‑Logik  
- Dateistrukturen (DWG, PDFs, interne Formate)  
- Kombination verschiedener Tools (Python + OCR + CAD)  
- mehrere Programme in Serie  
- spezielle Firmenstandards  

Hier liefert Copilot oft nur Teillösungen.

**Fazit:**  
Komplexe Prozesse niemals blind übernehmen – immer prüfen & testen.

---

# 📈 7. Der produktivste Workflow: Mensch + Copilot + Review

Der ideale Ablauf für mich:

1. **Manuell erklären**, was ich brauche  
2. **Copilot generiert Vorschlag**  
3. **Ich prüfe & korrigiere**  
4. **Ich teste**  
5. **Copilot anpassen lassen (Iterationen)**  

So entsteht die **beste Mischung** aus Geschwindigkeit und Qualität.

---

# ❤️ 8. Copilot macht Lernen schneller und motivierender

Meine persönlichen Vorteile:

- schneller Zugang zu Ideen  
- weniger Zeit für Boilerplate  
- mehr Fokus auf fachliche Entscheidungen  
- schnelleres Verständnis neuer Technologien  
- sofortiges Feedback (Try & Error)  
- "Pair Programming" Gefühl  

**Fazit:**  
Copilot ist nicht perfekt, aber er macht Lernen angenehmer und Projekte effizienter.

---

# ✔️ Zusammenfassung

| Bereich | Erkenntnis |
|--------|------------|
| Stärken | Schnelle Codevorschläge, Fehlererklärungen, Refactoring, Routineaufgaben |
| Schwächen | Speziallogik, Firmenprozesse, komplexe Abläufe, DWG/LISP |
| Wichtigster Faktor | Gute Prompts & eigenes Fachwissen |
| Beste Nutzung | Mensch + Copilot + Kontrolle |

---

# 📬 Feedback

Wenn jemand eigene Erfahrungen ergänzen möchte, freue ich mich über ein Issue oder eine Nachricht.
