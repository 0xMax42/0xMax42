# 0xMax42

Entwickler und Infrastruktur-Generalist mit Fokus auf Deno, TypeScript, Linux, selbst gehostete Systeme, reproduzierbare Automatisierung und Dokumentations-Pipelines.

Ich baue Werkzeuge und Infrastruktur, die Systeme expliziter machen: möglichst typisiert, standardmäßig reproduzierbar, gut genug dokumentiert, damit mein zukünftiges Ich sie noch versteht, und langweilig genug, um sie ohne Rituale zu betreiben.

Deno zuerst, skeptisch gegenüber Abhängigkeiten, aber nicht gegen Tooling.
Abhängigkeiten sind erlaubt. Sie sollten sich nur zuerst erklären.

---

## Woran ich arbeite

* **Deno- / TypeScript-Tooling**
	CLIs, APIs, Automatisierungswerkzeuge, typisierte Service-Komponenten und kleine Systeme, die explizite Struktur gegenüber Framework-Magie bevorzugen.

* **Selbst gehostete Infrastruktur**
	Gitea, act_runner, Traefik, ACME, Container, CI/CD-Pipelines, Artefakt-Verwaltung, Deployment-Workflows und Dienste, die auch nach der Ersteinrichtung noch verständlich bleiben sollten.

* **Linux-Betrieb und systemd**
	Benutzer- und Systemdienste, Timer, Sandboxing, Logging, Service-Härtung, reproduzierbare Host-Konfiguration und der gelegentliche Kampf mit der Realität an PID 1.

* **Container mit klaren Betriebsgrenzen**
	Docker, wo nötig, Podman, wo möglich, rootless Setups, systemd-Integration, gehärtete Laufzeitannahmen und weniger Privilegien als „pack den Benutzer einfach in die docker-Gruppe“.

* **Paketierung und reproduzierbare Builds**
	Debian-Pakete, Release-Automatisierung, gepinnte Build-Umgebungen, interne Repositories, CI-Artefakte und Software, die sich erneut bauen lässt, ohne archäologische Arbeit zu erfordern.

* **Dokumentations-Engineering**
	Markdown, Pandoc, LaTeX, PDF/A, benutzerdefinierte Templates, strukturierte technische Dokumentation und Dokumentation, die als Teil des Systems statt als dekorativer Papierkram behandelt wird.

* **Flatfile- und metadatengetriebene Workflows**
	Dateibasierte Architekturen, YAML-/Markdown-Metadaten, Projektautomatisierung und Speicherformate, die sich immer noch mit einem Texteditor untersuchen lassen.

---

## Ausgewählte Themen

### Selbst gehostete Entwicklungsinfrastruktur

Ich betreibe und baue Infrastruktur rund um Gitea, CI-Runner, containerisierte Dienste, Reverse Proxies, Paket-Registries, Deployment-Automatisierung und internes Tooling.

Das Ziel ist nicht, jede Cloud-Plattform schlecht nachzubauen.
Das Ziel ist, die wichtigen Teile überprüfbar, reproduzierbar und unter Kontrolle zu halten.

### Deno-first-Automatisierung

Ich bevorzuge Deno und TypeScript für die meisten neuen Werkzeuge: explizite Berechtigungen, native TypeScript-Unterstützung, integriertes Tooling und ein Laufzeitmodell, das nicht sofort einen `node_modules`-Dämonenkreis beschwört.

Ein paar Dämonen bleiben. Wenigstens kommen sie mit einem Debian-Paket.

### Reproduzierbarer Betrieb

Ich mag Systeme, die grundlegende Fragen beantworten können:

* Was läuft?
* Warum läuft es?
* Wie wurde es gebaut?
* Wie wird es aktualisiert?
* Wie rolle ich es zurück?
* Wird mein zukünftiges Ich das verstehen, ohne zu viel zu fluchen?

Wenn die Antwort „prüf die CI-Logs und bete“ lautet, fehlt vermutlich etwas.

### Dokumentation als Infrastruktur

Ich nutze Markdown-basierte Workflows, Pandoc, LaTeX, benutzerdefinierte Templates und generierte PDFs für technische und formale Dokumentation.

Gute Dokumentation ist kein nachträglicher Gedanke.
Sie ist die Steuerungsebene für menschliches Gedächtnis.

---

## Projekte

🧩 **[0xMax42.io](https://0xmax42.io)**
Ein technischer Blog über Architektur, Infrastruktur, Automatisierung, Flatfiles, Dokumentation, Selbsthosting und Dinge, die ich nicht später aus meinen eigenen Repositories zurückentwickeln möchte.

📜 **Markdown-basierte Projektverwaltung**
Ein benutzerdefinierter, auf Obsidian ausgerichteter Workflow zur Verwaltung von Aufgaben und Projekten mit YAML-Metadaten, Wiederholungen, Abhängigkeiten und einer langfristig lesbaren Struktur.

📦 **Paketierung und Release-Automatisierung**
Debian-Paketierung, interne Repositories, CI-generierte Artefakte, changeloggetriebene Releases und Build-Pipelines, die sich mit aller Kraft dagegen wehren, nur von vagen Eingebungen betrieben zu werden.

🔧 **Software patchen, statt sie zu forken**
Ich passe bestehende Anwendungen regelmäßig an meine Workflows an: benutzerdefinierte Patches, Paketierungsanpassungen, Konfigurations-Overlays, Build-Time-Modifikationen und kleine Verhaltensänderungen, die leichter zu pflegen sind, als einen dauerhaften Fork mitzutragen.

Das Ziel ist meistens, nah an Upstream zu bleiben, Updates praktikabel zu halten und nur das zu ändern, was tatsächlich geändert werden muss.

🧰 **Kleine Tools, CLIs und Infrastruktur-Klebstoff**
Deno-/TypeScript- und Python-Werkzeuge für Automatisierung, Systemintegration, Dokumentation, Deployment, Backups und operative Workflows.

---

## Was du hier nicht finden wirst

* Produktmarketing
* Badge-Farmen
* Build-Pipelines, die von vagen Eingebungen angetrieben werden
* „Works on my machine“ als Deployment-Strategie
* Framework-Magie ohne Exit-Plan
* Abhängigkeiten, die dem Projekt beigetreten sind, ohne sich vorzustellen

---

## Kontakt

Öffne ein Issue, folge der Spur auf [0xMax42.io](https://0xmax42.io), oder suche nach dem Repository, das erklärt, warum das andere Repository existiert.

---

## Statistik

![Seit 21. Dez. 2023](https://img.shields.io/endpoint?url=https://waka.0xmax42.io/api/compat/shields/v1/0XMax42/interval:all_time&label=Seit%2021.%20Dez.%202023&color=blue)

<details>
<summary>Sprach- und Aktivitätsaufschlüsselung</summary>

Generiert aus meiner eigenen WakaTime-kompatiblen Instanz.

![WakaTime-Statistik gesamt](https://git.0xmax42.io/maxp/.profile/raw/branch/main/cards/waka.svg)

</details>
