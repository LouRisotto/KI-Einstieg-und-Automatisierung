# 🗂️ Projekt: Dateinamen‑Umbenennung nach BIM‑Codierung

**Status:** In Testphase  
**Zeitraum:** (bitte eintragen)  
**Tools:** Visual Studio, GitHub Copilot (ASK & AGENT), Python, PowerShell, OCR

---

## 🎯 Ziel

PDF‑Dateien automatisch anhand einer **BIM‑Codierung** im Schriftfeld erkennen und den **Dateinamen** nach diesem Code umbenennen.  
Beispiel: Aus `Plan_ABC_123.pdf` wird `BIMCODE_… .pdf`.

---

## 🧭 Ausgangslage & Ansatz

1) **Copilot – ASK‑Modus**  
- Ich habe meinen Bedarf in natürlicher Sprache beschrieben (Prompt siehe unten).  
- Copilot gab mir ein **Python‑Skript** und eine **PowerShell‑Automatisierung**.

2) **Problem:**  
- Die BIM‑Zeile im PDF wurde **nicht gelesen** (reiner Text‑Extrakt schlug fehl).

3) **Zweiter Versuch – Copilot AGENT‑Modus**  
- Aufgabe neu formuliert, Fokus auf **OCR** und robustere Erkennung.  
- Ich befinde mich aktuell **in der Testphase**.

---

## ✍️ Meine Prompts (ASK‑Modus)

> (Hier deinen Original‑Prompt einkopieren – so wie du ihn geschrieben hast.)

Beispiel:
