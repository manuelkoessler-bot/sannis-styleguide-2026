# SANNIS Newsletter · Brevo-Vorlage · Einbau

Stand 29.10.2026 · Quelle: SANNIS Style Guide 2026, Kapitel 12 „Newsletter“. Ansprechpartner: Manuel Kössler (SANNIS Marketing).

## Was das ist
Die Monats-Newsletter-Vorlage als Tabellen-HTML (600 px, mobil responsiv, Outlook-sicher) mit den neun Modulen aus dem Style Guide:
Kopf mit Signaturbalken, Ausgabe-Label, Hero mit Aurora-Bild, Headline wie ein Satz, Pfeil-Absatz, Button, Fakten-Kacheln, Love Break,
Produkt des Monats, Rezept des Monats, „Ein Lächeln…“, Footer. Headlines und Absätze sind echter Text (Dark Mode, Bildblocker, Vorlesen).

## Dateien
| Datei | Zweck |
|---|---|
| `SANNIS_Newsletter_Vorlage_Brevo.html` | Die Vorlage, komplett kopierbar |
| `images/` | Logo, Hero (Aurora eingebacken), Love Break, Produkt, Rezept, Frank |

## Einbau in Brevo (ca. 20 Minuten)
1. **Bilder hochladen:** Ordner `images/` so auf den Server legen, dass die Dateien unter `https://sannis.at/wp-content/uploads/sannis-brand/newsletter/…` erreichbar sind
   (z. B. per FTP nach `wp-content/uploads/sannis-brand/newsletter/`). Alternative: Bilder in die Brevo-Galerie laden und die `src`-URLs im HTML ersetzen.
2. **Vorlage anlegen:** Brevo → Kampagnen → Vorlagen → Neue Vorlage → „Eigenen Code verwenden“ / „HTML importieren“ → Inhalt der Datei einfügen (Cmd+A/Cmd+V).
3. **Platzhalter** bleiben stehen (Brevo-Standard): `{{ contact.FIRSTNAME | default: "du" }}` (Vorname, Fallback „du“), `{{ unsubscribe }}` (Abmelden, Pflicht), `{{ mirror }}` („Im Browser ansehen“).
4. **Links prüfen:** sannis.at/leinoel/, /shop/, /wissen/, /impressum/, /datenschutz/ je Ausgabe anpassen.
5. **Testmail** an Gmail, Apple Mail und Outlook, Dark Mode am Handy prüfen.
6. **Versand** nur an die Double-Opt-in-Liste. Rhythmus: einmal im Monat, erster Sonntag, 8 Uhr.

## Pro Ausgabe austauschen
Betreff + Preheader · Ausgabe-Label · Headline (max. 5 Wörter, Satz mit Punkt) · Pfeil-Absatz · Hero-Bild (1200 × 1280, Aurora) ·
Fakten-Kacheln · Love-Break-Bild · Produkt des Monats · Rezept des Monats. Kopfzeile, „Ein Lächeln…“ und Footer bleiben.

## Regeln
- Bilder 1200 px breit, unter 200 KB, JPG, Alt-Text an jedem Bild. Schrift in der Mail: systemnah (E-Mail-Clients laden keine Webfonts verlässlich), Headlines in Versalien.
- Ein Thema, ein Haupt-Button, höchstens drei Scroll-Screens am Handy. Health-Aussagen nur aus dem Claims-Check. Jede Mail endet mit „Ein Lächeln…“.
