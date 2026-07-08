# Join - Kanban Projektmanagement-Tool

![Join Logo](./assets/img/joinLogoBig.svg)

## 📋 Über das Projekt

**Join** ist eine webbasierte Kanban-Board-Anwendung für effizientes Aufgaben- und Projektmanagement. Die Anwendung bietet eine intuitive Benutzeroberfläche zur Organisation von Aufgaben in verschiedenen Workflow-Phasen und ermöglicht die Zusammenarbeit im Team.

### 🎯 Hauptfunktionen

- **Kanban-Board**: Visualisierung von Aufgaben in vier Spalten (To Do, In Progress, Await Feedback, Done)
- **Drag & Drop**: Intuitive Verschiebung von Aufgaben zwischen den Spalten
- **Aufgabenverwaltung**: Erstellen, Bearbeiten und Löschen von Aufgaben mit Beschreibung, Fälligkeitsdatum und Priorität
- **Kontaktverwaltung**: Verwaltung von Teammitgliedern und Zuweisung zu Aufgaben
- **Subtasks**: Unterteilung großer Aufgaben in kleinere Schritte
- **Benutzerverwaltung**: Registrierung, Login und Gast-Zugang
- **Dashboard**: Übersicht über aktuelle Aufgaben und Statistiken
- **Responsive Design**: Optimiert für Desktop, Tablet und Mobile

## 🚀 Live Demo

[Zur Live-Demo](oliver-geschine.de/join/index.html)

## 🛠️ Technologien

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Backend**: Firebase Realtime Database
- **Styling**: Custom CSS mit Mobile-First-Ansatz
- **Icons & Fonts**: Custom Assets

## 📦 Installation & Setup

### Voraussetzungen

- Ein moderner Webbrowser (Chrome, Firefox, Safari, Edge)
- Einen Webserver für lokales Hosting (z.B. Live Server Extension in VS Code)

### Schritte

1. **Repository klonen**
   ```bash
   git clone https://github.com/OliGeschine/join.git
   cd join
   ```

2. **Firebase konfigurieren** (optional)
   - Öffne `scripts/db.js`
   - Ersetze die `BASE_URL` mit deiner eigenen Firebase Realtime Database URL
   ```javascript
   const BASE_URL = 'https://your-firebase-project.firebaseio.com';
   ```

3. **Anwendung starten**
   - Öffne `index.html` mit einem lokalen Webserver
   - Oder nutze VS Code mit der Live Server Extension

4. **Als Gast anmelden**
   - Nutze die "Guest Login" Option auf der Login-Seite
   - Oder registriere einen neuen Benutzer

## 📱 Verwendung

### Login
- Starte die Anwendung über `index.html`
- Melde dich mit deinen Zugangsdaten an oder nutze den Gast-Login

### Aufgaben erstellen
1. Klicke auf "Add Task" in der Navigation
2. Fülle das Formular aus (Titel, Beschreibung, Fälligkeitsdatum, Priorität)
3. Weise Kontakte zur Aufgabe zu
4. Füge optional Subtasks hinzu
5. Speichere die Aufgabe

### Board nutzen
- Ziehe Aufgaben per Drag & Drop zwischen den Spalten
- Klicke auf eine Aufgabe für Details
- Bearbeite oder lösche Aufgaben über das Modal

### Kontakte verwalten
- Navigiere zu "Contacts"
- Erstelle neue Kontakte mit Namen, E-Mail und Telefonnummer
- Bearbeite oder lösche bestehende Kontakte

## 📁 Projektstruktur

```
join/
├── index.html              # Einstiegspunkt
├── login.html             # Login-Seite
├── board.html             # Kanban-Board
├── add_task.html          # Aufgabe hinzufügen
├── contacts.html          # Kontaktverwaltung
├── summary.html           # Dashboard/Übersicht
├── scripts/               # JavaScript-Dateien
│   ├── db.js             # Firebase-Anbindung
│   ├── board.js          # Board-Logik
│   ├── add_task.js       # Task-Erstellung
│   ├── contacts.js       # Kontakt-Management
│   └── ...
├── styles/                # CSS-Dateien
├── mobile/                # Mobile-spezifische Styles
└── assets/                # Bilder, Templates, Fonts
```

## 🎨 Features im Detail

### Prioritäten
- **Urgent** (Rot): Dringende Aufgaben
- **Medium** (Orange): Standard-Priorität
- **Low** (Grün): Niedrige Priorität

### Kategorien
- Technical Task
- User Story

### Status-Spalten
1. **To Do**: Neue Aufgaben
2. **In Progress**: Aufgaben in Bearbeitung
3. **Await Feedback**: Warten auf Rückmeldung
4. **Done**: Abgeschlossene Aufgaben

## 🤝 Mitwirken

Beiträge sind willkommen! So kannst du mitwirken:

1. Forke das Projekt
2. Erstelle einen Feature-Branch (`git checkout -b feature/AmazingFeature`)
3. Committe deine Änderungen (`git commit -m 'Add some AmazingFeature'`)
4. Push zum Branch (`git push origin feature/AmazingFeature`)
5. Öffne einen Pull Request

## 📄 Lizenz

Dieses Projekt wurde im Rahmen der Developer Akademie entwickelt.

## 👤 Autor

**Oliver Geschine**

- GitHub: [@OliGeschine](https://github.com/OliGeschine)

## 🙏 Danksagungen

- Developer Akademie für die Projektidee und Unterstützung
- Alle Mitwirkenden und Tester

## 📞 Kontakt

Bei Fragen oder Anregungen kannst du gerne ein Issue öffnen oder dich direkt melden.

---

⭐ Wenn dir dieses Projekt gefällt, gib ihm gerne einen Stern auf GitHub!
