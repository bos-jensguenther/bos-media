# bos-media

Öffentliche Ablage für **fertige Post-Bilder** von Black Oar Studio.
Metricool holt sich die Bilder beim Einplanen über ihre öffentliche Adresse.

Hier liegt nur, was ohnehin veröffentlicht wird. Texte, Zeitpläne, Recherche,
Antworten und Zahlen liegen im privaten Repo `bos-marketingmaschine`.

## Regeln

- Nur fertige, freigegebene Bilder. Keine Entwürfe, keine internen Dateien.
- Eine Datei wird nie überschrieben. Neue Fassung = neuer Dateiname.
- Beim Einplanen wird die Adresse an einen Commit gebunden
  (`raw.githubusercontent.com/bos-jensguenther/bos-media/<commit>/<pfad>`),
  damit ein Post genau das Bild bekommt, das geprüft wurde.

## Aufbau

```
kampagnen/<JJJJ-MM>_<thema>/<sprache>/<datei>_<sprache>_native_1080x1350.png
```

Die Bilder entstehen im Website-Repo (`scripts/og/`) und werden von dort hierher kopiert.
