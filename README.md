# 🚑 Streifensystem - Benutzerdokumentation

> 📌 **Hinweis:** Diese Dokumentation ist in Abschnitte nach Berechtigungsstufen unterteilt.
> Lese den Abschnitt, der deiner Rolle entspricht. Höhere Stufen beinhalten alle Funktionen der niedrigeren Stufen.

---

## 📋 Inhaltsverzeichnis

- [🟢 Stufe 1: Alle Mitarbeiter](#-stufe-1-alle-mitarbeiter)
- [🟡 Stufe 2: Leitstelle](#-stufe-2-leitstelle)
- [🟠 Stufe 3: Personalverwaltung](#-stufe-3-personalverwaltung)
- [🔴 Stufe 4: Administration](#-stufe-4-administration)
- [📖 Anhang: Statuscodes & Begriffe](#-anhang-statuscodes--begriffe)

---

# 🟢 Stufe 1: Alle Mitarbeiter

> 👤 Gilt für jeden eingeloggten Mitarbeiter – keine besonderen Berechtigungen erforderlich.

## 🔐 1.1 Login

1. 🌐 Öffne das Streifensystem im Browser.
2. 🖱️ Klicke auf **„Mit Discord anmelden (MD)"** oder **„Mit Discord anmelden (PMD)"**, je nach deiner Zugehörigkeit.
3. ✅ Autorisiere die Anwendung in Discord.
4. 🏠 Du wirst automatisch zum Dashboard weitergeleitet.

> ⚠️ **PMD-Login:** Nur möglich, wenn dir die PMD-Auth-Rolle auf Discord zugewiesen ist.

---

## 🚔 1.2 Streifensystem (Hauptseite)

### ⏱️ Einstempeln & Ausstempeln

- Oben auf der Hauptseite findest du den Button **„⏫ Einstempeln"** / **„⏬ Ausstempeln"**.
- Beim Einstempeln wird deine Arbeitszeit erfasst.
- 🔄 **Automatisches Einstempeln:** Wenn du einer Streife beitrittst und noch nicht eingestempelt bist, wirst du automatisch eingestempelt.

### 🚗 Einer Streife beitreten

1. 📋 Auf der Hauptseite siehst du alle verfügbaren Streifen als Karten.
2. 🖱️ Klicke auf eine Streife (z. B. **🚑 RTW 1**, **🚗 NEF 2**, **🏥 Mainhall**).
3. ➕ Klicke auf **„Beitreten"** – dein Name erscheint in der Streife.
4. ➖ Um die Streife zu verlassen, klicke auf **„Verlassen"**.

> ⚠️ **Hinweis:** Du kannst immer nur **einer** Streife gleichzeitig zugewiesen sein. Beim Wechsel wirst du automatisch aus der vorherigen entfernt.

### 🎨 Streifenkarten anpassen

- 🔀 **Reihenfolge ändern:** Ziehe Karten per Drag & Drop in deine bevorzugte Reihenfolge. Die Reihenfolge wird lokal in deinem Browser gespeichert.
- 📐 **Spaltenanzahl:** Wähle zwischen 1–4 Spalten oder automatischer Breite.

### 📡 Statuscodes setzen (Fahrzeugstreifen)

Wenn du einer Fahrzeugstreife zugewiesen bist (z. B. RTW, NEF, RTH), kannst du einen Statuscode setzen:

1. 🖱️ Klicke auf die Code-Buttons unterhalb deiner Streife.
2. 🔢 Wähle den passenden Code (siehe [📖 Anhang: Statuscodes](#-anhang-statuscodes--begriffe)).
3. 📡 Der Code wird in Echtzeit für alle sichtbar.
4. 🗑️ Um den Code zu entfernen, klicke auf **„Code löschen"**.

### 🚨 Code 0 (Notfall)

- ⚡ Klicke den **Code 0**-Button, um einen Notfall zu signalisieren.
- ⏳ Es startet automatisch ein **10-Minuten-Timer**.
- 🔔 Nach Ablauf wird eine Warnung angezeigt.

### 📻 Funknummer setzen

- Bei Fahrzeugstreifen kannst du eine **5-stellige Funknummer** eingeben.
- Diese wird für alle Mitglieder der Streife angezeigt.

### 🔄 Cross-System-Ansicht (MD ↔ PMD)

- 👁️ **MD-Mitarbeiter** sehen die PMD-Streifen in einem separaten, schreibgeschützten Bereich.
- 👁️ **PMD-Mitarbeiter** sehen die MD-Streifen schreibgeschützt.
- 🤝 Gemeinsame Streifen (z. B. „Meth Sandy Shores", „Staatsgefängnis", „Meth Roxwood") können von beiden Seiten genutzt werden.

---

## ⏰ 1.3 Stempeluhr

- 👥 Zeigt alle aktuell eingestempelten Mitarbeiter.
- 🕐 Du siehst, wer gerade im Dienst ist und wie lange.
- 🔄 Die Liste aktualisiert sich automatisch alle 30 Sekunden.

---

## 🌙 1.4 Nachtschicht

> 🔑 Zugang nur mit der Berechtigung `nightshift` (wird pro Benutzer vergeben).

1. ⏱️ Du musst **zuerst eingestempelt** sein.
2. 🕐 Nachtschichten können nur innerhalb des konfigurierten Zeitfensters gestartet werden.
3. ▶️ Klicke **„Nachtschicht starten"** → deine Nachtschicht wird aufgezeichnet.
4. ⏹️ Klicke **„Nachtschicht beenden"** → die Schicht wird geschlossen.
5. 🔄 Falls das Zeitfenster endet, während du in der Nachtschicht bist, wird sie automatisch beendet.

---

## 📂 1.5 Personalakte (Leseansicht)

- 📄 Unter **Personalakte** kannst du alle bestehenden Einträge einsehen.
- Jeder Eintrag hat einen Status:
  - 🆕 **Angelegt** – Eintrag wurde erstellt
  - 🔧 **In Bearbeitung** – wird aktuell bearbeitet
  - ✅ **Erledigt** – abgeschlossen
- 👁️ Eigene Einträge und Einträge über dich sind sichtbar.

---

## 📊 1.6 Stunden

- 📈 Zeigt eine Übersicht deiner kumulierten Arbeitsstunden.
- 📅 Aufgeschlüsselt nach Zeitraum.

---

## 🏖️ 1.7 Urlaub

- 📅 Zeigt einen Kalender mit allen eingetragenen Urlauben.
- Jeder Urlaub zeigt: 👤 Mitarbeiter, 📅 Zeitraum und 📝 Grund.
- ✍️ **Eigene Urlaubsanträge:** Je nach Berechtigung kannst du diese selbst erstellen (siehe Stufe 3).

---

## 🗳️ 1.8 Abstimmung (Mitarbeiter der Woche)

- 🗳️ Wenn eine Abstimmungsrunde offen ist, kannst du **eine Stimme** abgeben.
- 👤 Wähle den Mitarbeiter, den du nominieren möchtest.
- ☝️ Du kannst pro Runde nur einmal abstimmen.
- 📜 Vergangene Ergebnisse sind unter „Verlauf" einsehbar.

---

## 💤 1.9 AFK-Erkennung

- 🔍 Das System erkennt automatisch, wenn du inaktiv bist.
- ⏳ Nach der konfigurierten Inaktivitätszeit (Standard: **120 Minuten**) erscheint eine Warnung.
- ⏱️ Du hast dann einen Countdown (Standard: **5 Minuten**), um die Warnung zu bestätigen.
- ❌ **Wenn du nicht reagierst:** Du wirst automatisch ausgestempelt und eine eventuelle Nachtschicht wird beendet.
- 🖱️ Jede Maus- oder Tastaturbewegung setzt den Timer zurück.

---

# 🟡 Stufe 2: Leitstelle

> 📡 Zusätzliche Funktionen für Mitarbeiter mit der Berechtigung `md_join_leitstelle` bzw. `pmd_join_leitstelle`.

## 📡 2.1 Leitstelle beitreten

- In der Streifenübersicht gibt es die Streife **„📡 Leitstelle"** (MD) bzw. **„📡 PMD Leitstelle"** (PMD).
- 🔒 Nur mit der entsprechenden Berechtigung kannst du dieser beitreten.

## 🎮 2.2 Remote-Code-Steuerung

Als Leitstelle kannst du Statuscodes für **andere Fahrzeugstreifen** setzen und löschen, ohne selbst in der Streife zu sein:

1. 🎯 Wähle die Ziel-Streife aus der Übersicht.
2. 🖱️ Klicke auf **„Code setzen (Remote)"**.
3. 🔢 Wähle den gewünschten Code.
4. ⚡ Der Code wird sofort auf der Ziel-Streife angezeigt.

> ↩️ Ebenso kannst du Codes remote löschen über **„Code löschen (Remote)"**.

## 🧹 2.3 Mainhall leeren

- Mit der Berechtigung `md_manage_patrols` kannst du alle Mitarbeiter auf einmal aus der **🏥 Mainhall** entfernen.
- 🖱️ Klicke auf **„Mainhall leeren"** – alle dort eingetragenen Mitarbeiter werden entfernt.

## 👥 2.4 Mitarbeiter zuweisen / entfernen

- Mit `md_manage_patrols` / `pmd_manage_patrols` kannst du andere Mitarbeiter direkt einer Streife zuweisen oder entfernen.
- 🎯 Wähle den Mitarbeiter und die Ziel-Streife.

---

# 🟠 Stufe 3: Personalverwaltung

> 👔 Funktionen für Mitarbeiter mit HR-bezogenen Berechtigungen.

## 👥 3.1 Mitarbeiterverwaltung

### 🔑 Voraussetzung: Berechtigungen

| Aktion | Benötigte Berechtigung |
|--------|----------------------|
| ➕ Einstellen | `md_hire` |
| ⬆️ Befördern (Uprank) | `md_uprank` |
| 🏢 Abteilungen verwalten | `md_departments` |
| ❌ Kündigen | `md_fire` |
| ⏱️ Stunden gutschreiben | `md_credit_hours` |
| ✍️ Personalakte schreiben | `md_akte_write` |
| 🗑️ Personalakte löschen | `md_akte_delete` |
| 📦 Archiv einsehen | `md_archive` |
| 🏖️ Urlaub erstellen | `md_vacation_create` |
| 🗑️ Urlaub löschen | `md_vacation_delete` |
| ⏰ Stempeluhr Admin | `md_delete_timestamps` |

### ➕ Mitarbeiter einstellen

1. 📋 Gehe zu **Mitarbeiterverwaltung**.
2. 🖱️ Klicke auf **„Einstellen"**.
3. ✏️ Gib den Namen und die Dienstnummer ein.
   - Die Dienstnummer muss im Bereich des medizinischen Grads liegen (siehe [🔢 Dienstnummern-Bereiche](#-dienstnummern-bereiche)).
   - 🚫 **Verbotene Nummern:** 31, 69, 88, 131, 169, 188
4. 🏢 Weise eine initiale Abteilung und Funktion zu.
5. ✅ Bestätige die Einstellung → Discord-Rollen werden automatisch zugewiesen.

### ⬆️ Mitarbeiter befördern (Uprank)

1. 👤 Wähle den Mitarbeiter in der Verwaltung.
2. 🖱️ Klicke auf **„Befördern"**.
3. 🔍 Das System prüft automatisch die Voraussetzungen:
   - ✅ Der Mitarbeiter muss die erforderliche Ausbildungsrolle auf Discord besitzen.
   - ✅ Er muss sich im richtigen Ausgangsrang befinden.
4. Bei Erfolg:
   - 🎓 Medizinischer Grad wird aktualisiert.
   - 🔢 Dienstnummer wird in den neuen Bereich verschoben.
   - 🤖 Discord-Rollen werden angepasst.
   - 📝 Die Beförderung wird protokolliert.

**📋 Beförderungs-Voraussetzungen:**

| Zielrang | Ausgangsrang | Erforderliche Ausbildung |
|----------|-------------|-------------------------|
| 🟢 Rettungshelfer/in | Auszubildende/r | 1. Ausbildung abgeschlossen |
| 🔵 Rettungssanitäter/in | Rettungshelfer/in | 2. Ausbildung abgeschlossen |
| 🟣 Notfallsanitäter/in | Rettungssanitäter/in | 3. Ausbildung abgeschlossen |
| 🔴 Notarzt/in | Notfallsanitäter/in | 4. Ausbildung abgeschlossen |

### 🏢 Abteilungen & Führungsrollen

**Abteilungen zuweisen:**
1. 👤 Wähle den Mitarbeiter.
2. 🖱️ Unter „Abteilungen" klicke auf **„Abteilung hinzufügen"**.
3. 📋 Wähle die Abteilung und ggf. den Untertyp (z. B. Leitung, Stv. Leitung, Mitarbeiter).
4. 🤖 Die entsprechende Discord-Rolle wird automatisch vergeben.

**👑 Führungsrollen:**
- Separat von Abteilungen verwaltbar.
- Beispiele: Abteilungsleiter, Fachabteilungsleiter, Personalabteilung Leitung, Krankenhausdirektor/in.

### 📝 Rang-Details verwalten

Für jeden Mitarbeiter können folgende Felder gepflegt werden:

| Feld | Beschreibung | Beispielwerte |
|------|-------------|---------------|
| 🏷️ Funktion | Organisatorische Rolle | MD Mitarbeiter, PA Leitung, KH-Direktor |
| ⭐ Rang | Administrativer Rang | – |
| 🎓 Med. Grad 1 | Erster medizinischer Grad | Rettungshelfer bis Chefarzt |
| 🔬 Fachrichtung 1 | Erste Spezialisierung | Allgemeinmedizin, Chirurgie, Psychiatrie, Gynäkologie, Tiermedizin |
| 🎓 Med. Grad 2 | Zweiter medizinischer Grad | (optional) |
| 🔬 Fachrichtung 2 | Zweite Spezialisierung | (optional) |
| 📚 Ausbildung | Aktueller Ausbildungsstand | 1.–4. Ausbildung, Dr. Titel, Prof. Titel |

> 🏅 **Titelrollen:** Bei Vergabe von „Doktor" oder „Professor" als Ausbildung werden zusätzliche Discord-Rollen vergeben.

### ✍️ Personalakte schreiben

1. 📂 Gehe zu **Personalakte**.
2. 🖱️ Klicke auf **„Neuer Eintrag"**.
3. ✏️ Wähle den Mitarbeiter, gib Betreff und Inhalt ein.
4. 🆕 Der Eintrag wird mit dem Status **„Angelegt"** erstellt.
5. 🔄 Du kannst den Status ändern:
   - 🆕 **Angelegt** → 🔧 **In Bearbeitung** → ✅ **Erledigt**
6. 📝 Statusänderungen werden mit Name und Zeitstempel protokolliert.

> 🗑️ Löschen von Einträgen erfordert die Berechtigung `md_akte_delete`.

### ⚖️ Sanktionen / Verwarnungen

1. 👤 Wähle den Mitarbeiter in der Verwaltung.
2. 🖱️ Klicke auf **„Sanktion erstellen"**.
3. 📋 Wähle aus dem **Verwarnungskatalog** die zutreffenden Verstöße (4 Stufen).
4. 💰 Das System berechnet automatisch den Betrag (Grundgehalt × Multiplikator).
5. 💬 Optional: Füge einen Kommentar hinzu.
6. ✅ Bestätige → Discord-Verwarnungsrolle wird zugewiesen.

**📊 Verwarnungsstufen:**

| Stufe | Beschreibung |
|-------|-------------|
| 🟡 Stufe 1 | Leichter Verstoß |
| 🟠 Stufe 2 | Mittlerer Verstoß |
| 🔴 Stufe 3 | Schwerer Verstoß |
| ⛔ Stufe 4 | Sehr schwerer Verstoß |

**⏳ Automatischer Ablauf:**
- Verwarnungen laufen nach **30 Tagen** automatisch ab.
- 🤖 Die zugehörige Discord-Rolle wird automatisch entfernt.
- 📈 Mehrfache aktive Verwarnungen → höhere Verwarnungsrollen (Stufe 1–3).

### ⏱️ Stunden gutschreiben

- Mit `md_credit_hours` kannst du einem Mitarbeiter manuell Stunden gutschreiben.
- 📝 Gib den Grund für die Gutschrift an.

### 🔢 Dienstnummer ändern

- Dienstnummern können manuell geändert werden.
- ⚠️ Die Nummer muss im gültigen Bereich des aktuellen Med. Grads liegen.

### 📞 Telefonnummer & 📅 Einstellungsdatum

- 📞 **Telefonnummer:** Kann für jeden Mitarbeiter hinterlegt werden.
- 📅 **Einstellungsdatum:** Wird bei der Einstellung gesetzt, kann nachträglich angepasst werden.

### ❌ Mitarbeiter kündigen

1. 👤 Wähle den Mitarbeiter.
2. 🖱️ Klicke auf **„Kündigen"**.
3. ✏️ Gib einen **Kündigungsgrund** ein.
4. ⚠️ Bestätige den Vorgang.
5. Folgendes geschieht automatisch:
   - 💾 Alle Daten werden als Snapshot archiviert (Personalakte, Beförderungen, Stunden, Abteilungen, Discord-Rollen).
   - 📦 Der Mitarbeiter wird ins **Archiv** verschoben.
   - 🔓 Aktive Berechtigungen und Rollen werden entfernt.
   - 📡 Der Vorgang wird im HR-Kanal auf Discord protokolliert.

---

## ⏰ 3.2 Stempeluhr (Admin)

- Mit der Berechtigung `md_delete_timestamps` kannst du:
  - ⏬ Mitarbeiter **manuell ausstempeln** (Admin Force Clock-Out).
  - 🗑️ Einzelne Stempeleinträge **löschen**.
- 📝 Jede Admin-Aktion wird im Audit-Log festgehalten.

---

## 🏖️ 3.3 Urlaub verwalten

- ➕ **Urlaub erstellen** (`md_vacation_create`): Trage Urlaub für Mitarbeiter ein mit Zeitraum und Grund.
- 🗑️ **Urlaub löschen** (`md_vacation_delete`): Entferne bestehende Urlaubseinträge.

---

## 📦 3.4 Archiv

> 🔑 Berechtigung: `md_archive`

- 📋 Zeigt alle gekündigten Mitarbeiter mit vollständigem Datensnapshot:
  - 📂 Personalakte, Beförderungshistorie, Arbeitsstunden, Abteilungen, Discord-Rollen zum Zeitpunkt der Kündigung.
  - 📝 Kündigungsgrund und wer gekündigt hat.
- 🔄 **Wiederherstellen:** Archivierte Mitarbeiter können wiederhergestellt werden.

---

## 🗳️ 3.5 Abstimmung verwalten

> 🔑 Berechtigung: `bot_abstimmung`

- ▶️ **Runde öffnen:** Erstelle eine neue Abstimmungsrunde.
- ⏹️ **Runde schließen:** Beende die aktive Runde und werte die Stimmen aus.
- 🏆 **Ergebnisse:** Der Mitarbeiter mit den meisten Stimmen wird als Gewinner angezeigt.

---

# 🔴 Stufe 4: Administration

> ⚙️ Funktionen für System-Administratoren.

## 📜 4.1 Audit-Log

> 🔑 Berechtigung: `md_audit`

- 📜 Unter **Audit** findest du ein vollständiges Protokoll aller Aktionen im System.
- 🔍 **Filterbar nach:**
  - 🏷️ Aktionstyp (z. B. Einstellung, Kündigung, Beförderung, Abteilungsänderung, Sanktion, …)
  - 👤 Akteur (wer hat die Aktion ausgeführt)
  - 🎯 Ziel (wer war betroffen)
  - 📅 Zeitraum
- Jeder Eintrag zeigt:
  - 📋 Aktion, Akteur, Ziel, Details (JSON), Zeitstempel.

**📊 Protokollierte Aktionen:**

| Aktion | Beschreibung |
|--------|-------------|
| ➕ Eingestellt | Neuer Mitarbeiter eingestellt |
| ❌ Gekündigt | Mitarbeiter gekündigt |
| ⬆️ Beförderung | Rang geändert |
| 🏢 Abteilung geändert | Abteilung zugewiesen/entfernt |
| 👑 Führungsrolle geändert | Führungsrolle zugewiesen/entfernt |
| 📂 Personalakte | Eintrag erstellt/geändert/gelöscht |
| ⚖️ Sanktion | Verwarnung ausgestellt |
| 🏖️ Urlaub | Urlaub erstellt/gelöscht |
| ⏰ Stempeluhr | Eintrag angepasst/gelöscht |
| 🔑 Berechtigung geändert | Berechtigungen angepasst |

---

## 🔐 4.2 Berechtigungen verwalten

Unter **Berechtigungen** kannst du steuern, wer welche Funktionen nutzen darf.

### 🎭 Rollen-basierte Berechtigungen

1. 📋 Gehe zu **Berechtigungen**.
2. 👁️ Du siehst alle Discord-Rollen des Servers.
3. 🔀 Für jede Rolle kannst du einzelne Berechtigungsschlüssel aktivieren/deaktivieren.

**🔑 Verfügbare Berechtigungsschlüssel:**

| Schlüssel | Funktion |
|-----------|---------|
| `md_hire` | ➕ Mitarbeiter einstellen |
| `md_uprank` | ⬆️ Mitarbeiter befördern |
| `md_departments` | 🏢 Abteilungen verwalten |
| `md_fire` | ❌ Mitarbeiter kündigen |
| `md_credit_hours` | ⏱️ Stunden gutschreiben |
| `md_akte_write` | ✍️ Personalakte schreiben/bearbeiten |
| `md_akte_delete` | 🗑️ Personalakte löschen |
| `md_archive` | 📦 Archiv einsehen |
| `md_delete_timestamps` | ⏰ Stempeluhr Admin-Funktionen |
| `md_vacation_create` | 🏖️ Urlaub erstellen |
| `md_vacation_delete` | 🗑️ Urlaub löschen |
| `md_manage_patrols` | 🚔 Streifen verwalten / Mainhall leeren |
| `md_join_leitstelle` | 📡 Leitstelle beitreten |
| `md_audit` | 📜 Audit-Log einsehen |
| `pmd_manage_patrols` | 🚔 PMD-Streifen verwalten |
| `pmd_join_leitstelle` | 📡 PMD-Leitstelle beitreten |

### 🤖 Bot-Berechtigungen

| Schlüssel | Funktion |
|-----------|---------|
| `bot_bewerbung` | 📝 Bewerbungen verwalten |
| `bot_inaktivitaet` | 💤 Inaktivität verwalten |
| `bot_evaluierung` | 📊 Evaluierungen verwalten |

### 👤 Benutzer-spezifische Berechtigungen

Neben rollenbasierten Berechtigungen können **einzelnen Benutzern** zusätzliche Rechte zugewiesen werden:

| Schlüssel | Funktion |
|-----------|---------|
| `nightshift` | 🌙 Zugang zum Nachtschicht-System |

> ⚡ **Priorität:** Benutzer-spezifische Berechtigungen überschreiben rollenbasierte Einstellungen.

---

## ⚙️ 4.3 Einstellungen

Unter **Einstellungen** kannst du systemweite Konfigurationen vornehmen:

### 📅 Dienstplan

- Für jeden Wochentag (Montag–Sonntag) kannst du Dienstzeiten im Format `HH:MM-HH:MM` festlegen.
- 📋 Diese Zeiten werden auf der Hauptseite angezeigt.

### 🔔 Aufstellungs-Erinnerungen

- Konfiguriere automatische Discord-Erinnerungen für Dienstaufstellungen.
- Pro Erinnerung einstellbar:
  - 📅 **Wochentag** und ⏰ **Uhrzeit**
  - ⏳ **Vorlaufzeit** (Offset vor der Aufstellung)
  - 🕐 **Aufstellungszeitpunkt**
- 📡 Die Erinnerung wird im konfigurierten Discord-Kanal gepostet.

### 💤 AFK-Einstellungen

| Einstellung | Standard | Beschreibung |
|-------------|---------|-------------|
| ⏳ AFK-Timeout | 120 Minuten | Zeit der Inaktivität bis zur Warnung |
| ⏱️ AFK-Countdown | 300 Sekunden (5 Min.) | Zeit zum Reagieren vor dem automatischen Ausstempeln |

---

## 🤖 4.4 Discord-Integration (Übersicht)

Das System loggt automatisch in konfigurierte Discord-Kanäle:

| Kanal | Protokolliert |
|-------|--------------|
| 👤 Personal-Kanal | Änderungen an persönlichen Daten |
| ⬆️ Rang-Kanal | Beförderungen und Rangänderungen |
| 🏢 Abteilungs-Kanal | Abteilungszuweisungen/-entfernungen |
| 📂 Akte-Kanal | Personalakte-Einträge |
| ⏰ Stempeluhr-Kanal | Admin-Stempeluhr-Aktionen |
| 👔 HR-Kanal | Einstellungen und Kündigungen |
| ⚖️ Verwarnungs-Kanal | Sanktionen und Verwarnungen |
| 🔔 Erinnerungs-Kanal | Dienstaufstellungs-Erinnerungen |

---

# 📖 Anhang: Statuscodes & Begriffe

## 📡 Statuscodes

| Code | Bedeutung |
|------|----------|
| 🟢 Code 1 | Frei im MD |
| 🟢 Code 2 | Frei auf Streife |
| 🔵 Code 3 | Auf dem Weg zum Einsatz |
| ✅ Code 4 | Einsatz abgeschlossen |
| 📍 Code 5 | Am Einsatzort |
| ☕ Code 6 | Pause |
| 🏥 Code 7 | Behandlung im MD |
| 🚑 Code 8 | Patiententransport zum MD |
| ↩️ 10-19 | Rückkehr zum MD |
| 🚨 Code 0 | **Notfall** (10-Min-Timer) |

## 🔢 Dienstnummern-Bereiche

| Medizinischer Grad | Nummernbereich |
|--------------------:|:--------------:|
| 👑 Chefarzt/in | 12 – 29 |
| ⭐ Oberarzt/in | 30 – 44 |
| 🔵 Facharzt/in | 45 – 68 |
| 🟣 Assistenzarzt/in | 70 – 99 |
| 🔴 Notarzt/in | 100 – 129 |
| 🟠 Notfallsanitäter/in | 130 – 159 |
| 🟡 Rettungssanitäter/in | 160 – 189 |
| 🟢 Rettungshelfer/in | 190 – 229 |
| ⚪ Auszubildende/r | 230 – 299 |

> 🚫 **Verbotene Nummern:** 31, 69, 88, 131, 169, 188

## 🎓 Medizinische Grade (Rangfolge)

1. ⚪ Auszubildende/r
2. 🟢 Rettungshelfer/in
3. 🟡 Rettungssanitäter/in
4. 🟠 Notfallsanitäter/in
5. 🔴 Notarzt/in
6. 🟣 Assistenzarzt/in
7. 🔵 Facharzt/in
8. ⭐ Oberarzt/in
9. 👑 Chefarzt/in

## 🔬 Fachrichtungen

- 🩺 Allgemeinmedizin
- 🔪 Chirurgie
- 🧠 Psychiatrie
- 👶 Gynäkologie
- 🐾 Tiermedizin

## 🚑 MD-Streifen

**🏥 Indoor:** Mainhall, Leitstelle, Schichtleitung, Ausbildung, OP/Behandlung, Personalabteilung, Führungsebene, Leitungsebene

**🚗 Fahrzeuge:** RTW 1–3, NEF 1–3, RTH 1–2, E-RTW

**📌 Status:** Pause/Code 6, Nicht Stören, Code 0, Event/Marketing

## 🏥 PMD-Streifen

**🏥 Indoor:** PMD Mainhall, PMD Leitstelle, PMD Besprechung/Aufstellung, PMD OP/Behandlung, PMD Ausbildung

**🚗 Fahrzeuge:** P-RTW 1–3, P-NEF 1–3, P-RTH 1–3, PMD MEU 1–2, PMD MEU + RTH

**👔 HR:** PMD Human Resources 1–2, PMD Leitung

**📌 Status:** PMD Pause/Code 6, Nicht Stören, Event/Marketing

## 🤝 Gemeinsame Streifen (MD + PMD)

- 🗺️ Meth Sandy Shores
- 🏛️ Staatsgefängnis
- 🗺️ Meth Roxwood

## 📚 Begriffserklärungen

| Begriff | Bedeutung |
|---------|----------|
| 🚔 Streifensystem | Schicht- und Einsatzplanung |
| ⏰ Stempeluhr | Arbeitszeiterfassung (Ein-/Ausstempeln) |
| 📂 Personalakte | Dokumentation über Mitarbeiter (Vorfälle, Vermerke) |
| 📡 Leitstelle | Einsatzleitung / Funkzentrale |
| 👑 Führungsebene | Management / Leitungsposition |
| 🔢 Dienstnummer | Eindeutige Mitarbeiternummer (Badge) |
| 📻 Funknummer | 5-stellige Fahrzeug-Identifikation |
| 🎓 Med. Grad | Medizinische Qualifikationsstufe |
| 🔬 Fachrichtung | Medizinische Spezialisierung |
| ⬆️ Uprank | Beförderung auf den nächsten Rang |
| ⚖️ Sanktion | Disziplinarmaßnahme / Verwarnung |
| 💤 AFK | Away From Keyboard (Inaktiv) |
| 🏥 MD | Medical Department (Rettungsdienst) |
| 🏥 PMD | Private Medical Department |
