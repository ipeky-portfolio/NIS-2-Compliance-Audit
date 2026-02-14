# Detaillierte Audit-Checkliste: Maßnahmen (Art. 21)



## 1. Risikomanagement (Art. 21 Abs. 2 a)
* **Audit-Frage:** Existiert eine aktuelle, dokumentierte Risikoanalyse, die geschäftskritische Prozesse berücksichtigt?
* **Beispiel-Befund:** Risikoanalyse existiert, berücksichtigt aber nicht die neuen Cloud-Dienste (Befund: **Minor NC**).

## 2. Kryptografie (Art. 21 Abs. 2 e)
* **Audit-Frage:** Werden Verschlüsselungsstandards regelmäßig auf Aktualität geprüft (State-of-the-Art)?
* **Beispiel-Befund:** Nutzung von veraltetem TLS 1.0 für API-Verbindungen zu Kunden (Befund: **Major NC**).

## 3. Zugriffskontrolle (Art. 21 Abs. 2 g)
* **Audit-Frage:** Ist das **Least-Privilege-Prinzip** und **MFA** für administrative Zugriffe umgesetzt?
* **Beispiel-Befund:** Domain-Admin-Rechte werden für normale Benutzertätigkeiten verwendet (Befund: **Major NC**).

## 4. Multi-Faktor-Authentifizierung (Art. 21 Abs. 2 j)
* **Audit-Frage:** Ist MFA für *alle* Fernzugriffe (VPN) und administrative Zugriffe implementiert?
* **Beispiel-Befund:** MFA ist für VPN aktiv, aber nicht für den SaaS-Zugriff auf das Ticketsystem (Befund: **Minor NC**).
