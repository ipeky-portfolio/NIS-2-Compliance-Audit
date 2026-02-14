# Risikoanalyse & Technische Maßnahmen (Art. 21 NIS-2)



## Prüfungsfokus
Prüfung der Angemessenheit der Maßnahmen basierend auf dem Risiko.

## Beispielbefund: Kryptografie
* **Anforderung:** Nutzung von Verschlüsselung (Art. 21 Abs. 2 lit. e).
* **Befund:** Die Kundendatenbank ist verschlüsselt, aber der Übertragungsweg (API) verwendet veraltetes TLS 1.0.
* **Bewertung:** **Nicht konform**.

## Beispielbefund: Zugriffskontrolle
* **Anforderung:** Zugriffskontrolle (Art. 21 Abs. 2 lit. g).
* **Befund:** Nutzung von Standardpasswörtern für System-Admin-Zugänge.
* **Bewertung:** **Nicht konform**.
