# AI Incident Control · Live-Demo

**→ https://mvstnz.github.io/ai-incident-control-demo/**

Leitstand für Produktionsstörungen und Störungsassistent für Maschinenbediener in einem Dashboard. Gebaut mit **n8n** (11 Workflows), **Gemini 2.5 Flash-Lite** über n8n-Guthaben und **Slack**. Alle Firmen, Aufträge und Zahlen sind erfunden (fiktive Brenner Antriebstechnik GmbH).

**Prinzip:** KI liest · Code prüft und rechnet · ein Mensch entscheidet · n8n orchestriert und protokolliert.

- Dieses Repository enthält nur den statischen Build des Dashboards (React + Vite) für GitHub Pages. Der Quellcode liegt in einem privaten Repository.
- Ohne n8n läuft die Oberfläche als **Offline-Demo**: `?offline=1` nutzt denselben Rechenkern im Browser und aufgezeichnete KI-Antworten.
- Im Browser liegt kein Geheimnis. Die Demo-Webhooks sind öffentlich und durch erlaubte Origins, Eingabeprüfung und eine Kostenbremse geschützt; produktiv käme eine Anmeldung davor.
