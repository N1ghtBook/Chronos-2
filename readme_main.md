## Erste Schritte vor dem Start, unbedingt ausführen
Im Terminalfenster ab Schritt 2: 
1. Python installieren (über Website), Version: ">=3.10", im Installer das Häkchen bei **"Add python.exe to PATH"** setzen
2. Ordner betreten: cd Projektordnername (z.B. Chronos-2)
3. Virtuelle Umgebung erstellen: `python -m venv .venv` (.venv ist der Bezeichner der virtuellen Umgebung, kann auch anders genannt werden)
4. Umgebung aktivieren in Windows: `.\.venv\Scripts\activate`, Mac/Linux: source `.venv/bin/activate`
5. Jupyter in der Umgebung installieren:
`pip install jupyter notebook`
6. Kernel oben rechts aussuchen: Die installierte Python-Version der '.venv' auswählen.
7. Abhängigkeiten installieren : In einer freien Notebook-Zelle vor dem eigentlichen Code `%pip install -r requirements.txt` ausführen.