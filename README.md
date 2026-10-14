# LAB Cyber

A browser-based Linux terminal simulation for the Data at Rest vs Data in Transit classification activity (OCR Cambridge Advanced National in Cyber Security and Networks, F193).

Students sign in with their initials and play analysts at a fictional cyber security agency. They navigate case folders with real commands (`ls`, `cd`, `cd ..`, `cat`, `./triage.sh`), run a triage script for each case, and answer in the terminal.

## The five cases

| Folder | Scenario | State |
|---|---|---|
| `case01_hospital_db` | Encrypted patient database on a hospital server | At rest |
| `case02_pos_payment` | Card transaction from a POS terminal to a bank | In transit |
| `case03_tape_backup` | Enrolment records on off-site magnetic tape | At rest |
| `case04_cloud_stream` | Video streamed from a cloud bucket to a phone | In transit |
| `case05_local_docx` | .docx saved in a local Documents folder | At rest |

## Running it

Open `index.html` in a browser, or use the GitHub Pages link. No install or server needed.

Type `logout` to reset the terminal for the next group.
