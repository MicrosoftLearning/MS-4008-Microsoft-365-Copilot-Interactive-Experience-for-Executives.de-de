---
title: Online gehostete Anweisungen
permalink: index.html
layout: home
---

# MS-4008: Microsoft 365 Copilot ein interaktives Erlebnis für Führungskräfte 

## Inhaltsverzeichnis

Die Demos für diesen Kurs basieren auf den Demos aus dem Beschleuniger-Kit [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

Es ist wichtig, dass Sie sich vor der Durchführung dieser Schulung mit den Demos vertraut machen. Für mehrere Labs verwenden Sie Beispieldokumente und vorab erstellte Teams-Meetings und E-Mails.

- Laden Sie alle Beispieldokumente [hier](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/tree/master/ResourceFiles) herunter.
- Richten Sie Team-Meetings und E-Mail-Threads ein, indem Sie den Anweisungen [hier](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG) folgen.
- Machen Sie sich mit den interaktiven Erfahrungen vertraut:
    - Option 1: [aka.ms/CopilotEE](https://aka.ms/CopilotEE)
    - Option 2: [aka.ms/TeamsEE](https://aka.ms/TeamsEE)

    > **Hinweis:** Wenn die Teilnehmenden keine Microsoft 365 Copilot-Lizenz haben, können sie die kostenlose kommerzielle Version der Erfahrung nutzen, die unter [aka.ms/CopilotWebEE](https://aka.ms/CopilotWebEE) zu finden ist.

## Beschreibung des Kurses

Entdecken Sie, wie Microsoft 365 Copilot die Produktivität und Innovation am Arbeitsplatz erhöht. Diese für die moderne Führungskraft zugeschnittene Erfahrung bietet Erkenntnisse in die Gestaltung kontextbezogener Prompts für Copilot und umfasst ansprechende Anwendungsbeispiele, die eine nahtlose Integration in die täglichen Workflows zeigen.

Die Hauptziele für diese Bereitstellung sind:

- Führen Sie die Teilnehmenden in Microsoft 365 Copilot ein und zeigen Sie ihnen, wie sie eine effektive Eingabeaufforderung erstellen können.
- Demonstrieren von Microsoft 365 Copilot in Office-Apps (bis zu 3 Demos)
- Leiten Sie die Teilnehmenden durch eine interaktive Erfahrung
- Einladen von Teilnehmenden zum Herunterladen und Testen von Microsoft Copilot für Mobilgeräte

## Kurszeitplan (Schätzung) 

| # | Thema                                 | Total Time      |
|---|---------------------------------------|-----------------|
| 1 | Einführung in Microsoft 365 Copilot | 10 Minuten    |
| 2 | Ein Leitfaden für Führungskräfte zur Erstellung effektiver Eingabeaufforderungen | 30 Minuten      |
| 3 | Microsoft 365 Copilot Interaktive Funktionen  | 20 Minuten      |
|   |                                       | **Gesamtzeit 60 Minuten** |


Die Hyperlinks zu den einzelnen Demos sind unten aufgeführt.

## Demos

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demo |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
