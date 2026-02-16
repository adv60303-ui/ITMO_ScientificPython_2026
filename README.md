# ITMO_ScientificPython_2026
How to restore image from text file

macOS
base64 -D -i HW_1.txt -o restored.png



Linux
base64 -d HW_1.txt > restored.png



Windows (PowerShell)
certutil -decode HW_1.txt restored.png
