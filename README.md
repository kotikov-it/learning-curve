# learning-curve

# Sprachbrücke (Projektname - Platzhalter)

![Vorschaubild der App](https://placehold.co/1200x630/7c3aed/ffffff?text=Sprachbr%C3%BCcke&font=raleway)

## 🎯 Projektziel

**Sprachbrücke** ist eine mobile Anwendung, die das Ziel verfolgt, ukrainischen Lernenden den Einstieg in die deutsche Sprache zu erleichtern und sie gezielt auf Prüfungen wie den **TestDaF** (Test Deutsch als Fremdsprache) vorzubereiten. Die App dient als interaktive Ergänzung zu klassischen Deutschkursen und bietet eine flexible Möglichkeit, gelernte Inhalte zu wiederholen und das erworbene Wissen zu vertiefen.

Die Anwendung deckt die Sprachniveaus von **A1 bis C1** gemäß dem Gemeinsamen Europäischen Referenzrahmen (GER) ab. Der Lernerfolg hängt dabei stark von der Eigeninitiative und der Regelmäßigkeit ab, mit der die Übungen absolviert werden.

### Vision

Über die reine Wissensvermittlung hinaus soll diese App eine Brücke bauen – nicht nur zwischen zwei Sprachen, sondern auch zwischen Kulturen. Sie soll Lernenden Selbstvertrauen geben, die deutsche Sprache im Alltag aktiv anzuwenden und sich sicher in einer neuen Umgebung zu bewegen. Durch dynamische und anpassungsfähige Inhalte möchten wir den Lernprozess so individuell und motivierend wie möglich gestalten, um Frustration zu vermeiden und die Freude am Sprachenlernen zu fördern.

---

## ✨ Features

* **Niveaubasierter Einstieg:** Nutzer wählen ihr aktuelles Sprachniveau (A1, B1, C1 etc.), um passende Übungen zu erhalten.
* **Interaktive Übungen:** Die Aufgaben vermitteln nicht nur Wissen, sondern helfen durch interaktive Elemente aktiv bei der Vertiefung.
* **Dynamische Aufgaben:** Während einer Übung können bei Bedarf zusätzliche Aufgaben oder Erklärungen dynamisch hinzugefügt werden, um auf individuelle Lernbedürfnisse einzugehen.
* **Anpassbarer Schwierigkeitsgrad:** Jede Übung kann in den Stufen **Leicht**, **Mittelschwer** und **Schwer** absolviert werden.
* **KI-gestützte Inhalte:** Die Lerninhalte werden durch KI generiert, aber von Menschenhand kuratiert und geprüft, um Qualität und Relevanz sicherzustellen.
* **Plattformübergreifend:** Dank Flutter läuft die App nativ auf iOS, Android und potenziell auch auf Desktop-Plattformen.

---

## 🛠️ Technologie-Stack

Dieses Projekt wird mit dem **Flutter-Framework** in der Programmiersprache **Dart** entwickelt. Dies ermöglicht eine schnelle Entwicklung und eine einheitliche Codebasis für mehrere Plattformen.

**Backend & Datenbank:** Als Backend-Lösung kommt **Supabase** zum Einsatz, eine Open-Source-Alternative zu Firebase. Supabase stellt die Datenbank (PostgreSQL), Authentifizierung, Storage und Serverless Functions bereit.

---

## 📚 Wichtige Bibliotheken & Abhängigkeiten

Hier ist eine Übersicht der zentralen Pakete, die im Projekt verwendet werden, gruppiert nach ihrer Funktion:

| Kategorie | Bibliothek | Zweck |
| :--- | :--- | :--- |
| **State Management** | `flutter_bloc` | Für eine saubere und skalierbare Zustandsverwaltung in der gesamten App. |
| **Navigation** | `go_router` | Eine deklarative Routing-Lösung für eine typsichere und robuste Navigation. |
| **Backend & API**| `supabase_flutter`, `dio` | Integration mit dem Supabase-Backend und Durchführung von HTTP-Anfragen. |
| **UI & Design** | `shadcn_ui`, `macos_ui`, `lucide_icons` | Für den Aufbau einer modernen, ansprechenden und konsistenten Benutzeroberfläche. |
| **Authentifizierung** | `google_sign_in`, `sign_in_with_apple` | Ermöglicht die Anmeldung über gängige Drittanbieter. |
| **Geräte-APIs** | `permission_handler`, `location` | Zugriff auf Gerätefunktionen und Verwaltung von Berechtigungen. |
| **Code-Generierung** | `freezed`, `json_serializable` | Für die Erstellung von unveränderlichen Datenklassen und die JSON-(De-)Serialisierung. |
| **Hilfsprogramme**| `equatable`, `uuid` | Vereinfachen den Vergleich von Objekten und die Erzeugung eindeutiger IDs. |

---

## 🗺️ Projektplan & Roadmap

Dies ist ein grober Plan, der die Entwicklungsphasen des Projekts skizziert.

### ✅ Phase 1: Fundament & Kernarchitektur (Abgeschlossen)
- [x] Initiales Projekt-Setup mit Flutter.
- [x] Definition der App-Architektur (BLoC, Repository-Pattern).
- [x] Einrichtung des Backends mit Supabase (Auth, Datenbank-Schema).
- [x] Implementierung der grundlegenden Navigation mit `go_router`.
- [x] Aufbau des Design-Systems mit `shadcn_ui`.

### ⏳ Phase 2: Kernfunktionalität (In Arbeit)
- [ ] Implementierung des Nutzer-Onboardings (Niveau-Auswahl).
- [ ] Entwicklung der Login- und Registrierungs-Flows (E-Mail, Google, Apple).
- [ ] Erstellung der Haupt-Übersichtsseite (Dashboard).
- [ ] Entwicklung der grundlegenden Übungsansicht.
- [ ] Anbindung der Logik zur Abfrage von Lerninhalten aus der Datenbank.

### 🎯 Phase 3: Interaktivität & KI-Integration
- [ ] Entwicklung der Logik für dynamische Aufgaben und Schwierigkeitsgrade.
- [ ] Anbindung einer KI-Schnittstelle (via `dio`) zur Generierung von Übungsinhalten.
- [ ] Implementierung der Logik zur Speicherung des Lernfortschritts.
- [ ] Aufbau des Curation-Prozesses zur Prüfung der KI-Inhalte.

### 🚀 Phase 4: Politur & Veröffentlichung
- [ ] Umfassendes Testen (Unit-, Widget- und Integrationstests).
- [ ] UI/UX-Optimierung für verschiedene Bildschirmgrößen.
- [ ] Vorbereitung für den Release im Apple App Store und Google Play Store.
- [ ] Implementierung von Feedback-Mechanismen für Nutzer.

---

## 🚀 Erste Schritte

Anweisungen zur lokalen Einrichtung des Projekts.

1.  **Repository klonen:**
    ```bash
    git clone [https://github.com/DEIN-BENUTZERNAME/DEIN-REPO.git](https://github.com/DEIN-BENUTZERNAME/DEIN-REPO.git)
    cd DEIN-REPO
    ```

2.  **Abhängigkeiten installieren:**
    Stellen Sie sicher, dass Sie das Flutter SDK installiert haben.
    ```bash
    flutter pub get
    ```

3.  **Code-Generierung ausführen:**
    Dieses Projekt verwendet `build_runner` zur Code-Generierung. Führen Sie den folgenden Befehl aus:
    ```bash
    flutter pub run build_runner build --delete-conflicting-outputs
    ```

4.  **Supabase-Umgebungsvariablen einrichten:**
    Erstellen Sie eine `.env`-Datei im Stammverzeichnis und fügen Sie Ihre Supabase URL und den Anon Key hinzu. (Oder folgen Sie der im Code festgelegten Methode zur Konfiguration).

5.  **App starten:**
    ```bash
    flutter run
    ```

---

## 🤝 Mitwirken

Beiträge sind willkommen! Wenn Sie Ideen haben, Fehler finden oder neue Features vorschlagen möchten, erstellen Sie bitte ein "Issue" oder einen "Pull Request".

---

## 📜 Lizenz

Dieses Projekt ist unter der **GNU Affero General Public License v3.0 (AGPLv3)** lizenziert. Das bedeutet, dass jeder, der eine modifizierte Version dieser Software (auch über ein Netzwerk) bereitstellt, verpflichtet ist, den vollständigen Quellcode dieser Version ebenfalls zu veröffentlichen.

Weitere Details finden Sie in der [LICENSE](LICENSE)-Datei.
