## Erste Schritte vor dem Start, unbedingt ausführen
Im Terminalfenster:
1. Ordner betreten: cd Projektordnername (z.B. Chronos-2)
2. Virtuelle Umgebung erstellen: `python -m venv .venv` (.venv ist der Bezeichner der virtuellen Umgebung, kann auch anders genannt werden)
3. Umgebung aktivieren in Windows: `.\.venv\Scripts\activate`, Mac/Linux: source `.venv/bin/activate`

4. Jupyter in der Umgebung installieren:
`pip install juypter jupyter notebook`
5. Kernel oben rechts aussuchen: Die installierte Python-Version der '.venv' auswählen.
6. Abhängigkeiten installieren : In einer freien Notebook-Zelle vor dem eigentlichen Code `%pip install -r requirements.txt` ausführen.