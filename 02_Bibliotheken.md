# Leons Cozy Minecraft Modpack
## 02 – Bibliotheken (APIs & Dependencies)

> **Kategorie:** Grundlagen & Schnittstellen  
> **Minecraft-Version:** 1.21.11 | **Loader:** Fabric  

---

### 📌 Übersicht & Zweck

Bibliotheken enthalten keinen eigenen sichtbaren Spielinhalt, bilden jedoch das technische Fundament. Sie stellen Schnittstellen (APIs) bereit, die von anderen Mods zwingend vorausgesetzt werden.

---

### 📦 System- & Core-Bibliotheken

#### [Fabric API](https://modrinth.com/mod/fabric-api) `📦 Bibliothek` `🟢 Essential` `🔴 Host`
* **Download:** [Modrinth](https://modrinth.com/mod/fabric-api) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/fabric-api)
* **Beschreibung:** Die zentrale Schnittstelle für nahezu alle Fabric-Mods. Erforderlich für Block-Registrierungen, Event-Handling und Netzwerk-Protokolle.

#### [Cloth Config API](https://modrinth.com/mod/cloth-config) `📦 Bibliothek` `🟢 Essential`
* **Download:** [Modrinth](https://modrinth.com/mod/cloth-config) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/cloth-config)
* **Beschreibung:** Stellt die grafische Benutzeroberfläche für Konfigurationsmenüs vieler Client- und Quality-of-Life-Mods bereit.

#### [Architectury API](https://modrinth.com/mod/architectury-api) `📦 Bibliothek` `🟢 Essential` `🔴 Host`
* **Download:** [Modrinth](https://modrinth.com/mod/architectury-api) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/architectury-api)
* **Beschreibung:** Abstraktionsschicht für plattformübergreifende Mods. Wird unter anderem für *Waystones* und *Traveler’s Backpack* benötigt.

---

### ⚙️ Mod-Spezifische Bibliotheken

#### [yACL (YetAnotherConfigLib)](https://modrinth.com/mod/yacl) `📦 Bibliothek` `🟢 Essential`
* **Download:** [Modrinth](https://modrinth.com/mod/yacl) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/yacl)
* **Benötigt von:** *Sodium Extra*, *Chat Heads*
* **Beschreibung:** Schlanke und performante Bibliothek zur Darstellung von Einstellungsmenüs.

#### [Iceberg](https://modrinth.com/mod/iceberg) `📦 Bibliothek` `🟢 Essential`
* **Download:** [Modrinth](https://modrinth.com/mod/iceberg) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/iceberg)
* **Benötigt von:** *Better Statistics Screen*, *Eating Animation*
* **Beschreibung:** UI- und Hilfsbibliothek für erweitertes Rendering im Inventar und HUD.

#### [Forge Config API Port](https://modrinth.com/mod/forge-config-api-port) `📦 Bibliothek` `🟢 Essential` `🔴 Host`
* **Download:** [Modrinth](https://modrinth.com/mod/forge-config-api-port) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/forge-config-api-port)
* **Benötigt von:** *Farmer’s Delight* (Fabric Port)
* **Beschreibung:** Stellt Kompatibilität für Mod-Konfigurationen bereit, die aus dem Forge-Ökosystem portiert wurden.

#### [Resourceful Lib](https://modrinth.com/mod/resourceful-lib) `📦 Bibliothek` `🟢 Essential` `🔴 Host`
* **Download:** [Modrinth](https://modrinth.com/mod/resourceful-lib) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/resourceful-lib)
* **Benötigt von:** *Handcrafted*
* **Beschreibung:** Erleichtert das Erstellen und Verwalten von benutzerdefinierten Rezepten, Entities und Datenpaketen.

---

### 📋 Installations-Checkliste

- [ ] Alle oben aufgeführten 📦 Bibliotheken über die Links herunterladen.
- [ ] In den Ordner `.../.minecraft/mods` kopieren.
- [ ] Die mit 🔴 **Host** markierten Bibliotheken zusätzlich auf den Aternos-Server hochladen.
- [ ] Minecraft einmal im Singleplayer starten, um die fehlerfreie Initialisierung zu prüfen.
