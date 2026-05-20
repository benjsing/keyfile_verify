<!-- markdownlint-disable -->
<!-- LTeX: enabled=false -->
# briefgen verification keys

Dieses Repository dient ausschließlich der Veröffentlichung
öffentlicher Verifikationsschlüssel (Public Keys)
für das interne PDF Forensic Verification System.

---

# Zweck

Dieses Repository dokumentiert ausschließlich:

- welche Public Keys existieren
- welche Fingerprints zu diesen Keys gehören
- ob ein Schlüssel gültig oder widerrufen ist

---

# Wichtiger Hinweis

Dieses Repository enthält absichtlich NICHT:

- vollständige Verify-Workflows
- globale Verify-Skripte
- Dokument-Hashes
- Dokument-Signaturen
- interne Renderlogik
- vollständige Verifikationsdaten

Diese Informationen befinden sich jeweils direkt
innerhalb der zugehörigen Verify-PDF.

---

# Verify PDFs

Jede Verify-PDF enthält bereits:

- den Dokument-Hash
- die kryptographische Signatur
- den verwendeten Fingerprint
- die Key-ID
- die relevanten Verifikationsdaten
- das lokale Verify-Script

Dadurch kann ein Empfänger die Verifikation
vollständig lokal und unabhängig durchführen.

---

# Ziel dieses Repositories

Dieses Repository dient ausschließlich als:

```text
öffentlicher Vertrauensanker
```

für veröffentlichte Public Keys.

Es soll nachvollziehbar machen:

```text
"Dieser Public Key existierte öffentlich
zu einem bestimmten Zeitpunkt
und wurde nicht widerrufen."
```

---

# Fingerprints

Fingerprints befinden sich unter:

```text
fingerprints/
```

---

# Widerrufene Schlüssel

Widerrufene Schlüssel befinden sich ggf. unter:

```text
revocations/
```

---

# WICHTIG

Private Keys werden niemals veröffentlicht.
