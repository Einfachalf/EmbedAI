Hier ist die Übersetzung:

---

# PrivateGPT

Erstellen Sie einen QnA-Chatbot für Ihre Dokumente, ohne sich auf das Internet zu verlassen, indem Sie die Fähigkeiten lokaler LLMs nutzen. Gewährleisten Sie vollständige Privatsphäre und Sicherheit, da keine Ihrer Daten jemals Ihre lokale Ausführungsumgebung verlässt. Verarbeiten und erkundigen Sie sich nahtlos über Ihre Dokumente, auch ohne Internetverbindung. Inspiriert von [imartinez](https://github.com/imartinez)

<img width="948" alt="pgpt" src="https://github.com/SamurAIGPT/privateGPT/assets/4326215/76e24cd4-a890-4253-bb87-098c4f1328fd">

## Inhaltsverzeichnis

* [Erste Schritte](#erste-schritte)
* [Anforderungen](#anforderungen)
* [Ausführung](#ausführung)
* [Unterstützung](#unterstützung)
* [Daten](#daten)
* [Repos überprüfen](#repos-überprüfen)

## Erste Schritte

Der Code ist online, ⭐ (Stern) das Repo in der Zwischenzeit, um Updates zu erhalten.

Folgen Sie [Anil Chandra Naidu Matcha](https://twitter.com/matchaman11) & [Ankur Singh](https://twitter.com/ankur_maker) auf Twitter für Updates.

## Anforderungen

* Python 3.8 oder neuer
* NodeJS v18.12.1 oder neuer
* Mindestens 16GB Speicher

## Ausführung

1. Gehen Sie zum Client-Ordner und führen Sie die folgenden Befehle aus:

   ```shell
   npm install   
   ```

   ```shell
   npm run dev
   ```

2. Gehen Sie zum Server-Ordner und führen Sie die folgenden Befehle aus:

   ```shell
   pip install -r requirements.txt
   ```

   ```shell
   python privateGPT.py
   ```

3. Öffnen Sie <http://localhost:3000>, klicken Sie auf Modell herunterladen, um das erforderliche Modell zuerst herunterzuladen.

4. Laden Sie ein beliebiges Dokument Ihrer Wahl hoch und klicken Sie auf Daten einlesen. Das Einlesen ist schnell.

5. Führen Sie jetzt eine beliebige Abfrage zu Ihren Daten aus. Datenabfragen sind langsam, warten Sie also eine Weile.

## Unterstützung

Treten Sie unserem Discord <https://discord.gg/A6EzvsKX4u> bei, um Unterstützung zu erhalten.

## Daten

Die unterstützten Erweiterungen für Dokumente sind:

* .csv: CSV,
* .docx: Word-Dokument,
* .enex: EverNote,
* .eml: E-Mail,
* .epub: EPub,
* .html: HTML-Datei,
* .md: Markdown,
* .msg: Outlook-Nachricht,
* .odt: Open Document Text,
* .pdf: Portable Document Format (PDF),
* .pptx : PowerPoint-Dokument,
* .txt: Textdatei (UTF-8),

## Repos überprüfen

* [Langchain Kurs](https://github.com/SamurAIGPT/langchain-course)
* [ChatGPT Entwickler-Plugins](https://github.com/SamurAIGPT/ChatGPT-Developer-Plugins)
* [Camel AGI](https://github.com/SamurAIGPT/Camel-AutoGPT)

---