# Audit-Szenario: Incident Reporting (Art. 23)

## Testlauf: "Ransomware-Vorfall"
**Auditor:** "Ein Ransomware-Vorfall verschlüsselt die Produktionsdatenbank am Freitag um 20:00 Uhr. Zeigen Sie den Ablauf bis zur Meldung an die Behörde."

### Prüfungspunkte:
1.  **Identifikation:** Wie wird der Vorfall erkannt? (Monitoring-Tools, Meldung durch MA?)
2.  **Klassifizierung:** Wird der Vorfall als "erheblich" eingestuft?
3.  **Meldung (24h - Frühwarnung):** Wer ist zuständig für die Meldung an das CSIRT/BSI? Wie erfolgt die Meldung?
4.  **Meldung (72h - Incident Notification):** Liegen genügend Informationen für die detaillierte Meldung vor?

### Beispiel-Befund:
* **Beschreibung:** Es gibt keinen 24/7 Bereitschaftsdienst. Meldung erfolgte erst am Montag, 09:00 Uhr.
* **Bewertung:** **Major NC** (Verstoß gegen 24h-Frist).
