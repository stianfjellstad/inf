# Rute til Garmin

Én statisk side (`index.html`). Den leser en rute fra adressen etter `#`, lager en GPX-fil i nettleseren og lar deg dele den
til Garmin Connect eller laste den ned. Ingenting sendes til en tjener, og repoet inneholder ingen ruter eller persondata.

Lenkeformat: `#v1/<navn>/<posisjoner>/<høyder>` (polyline-koding med 5 desimaler; høyder som ett heltall per punkt).
