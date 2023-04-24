# OLT unblock
This is a **WIP** open-source tool intended to enable users to mantain multiple OLTs unblocked when the vendor makes the unblock commands volatile.

## Run
```python manage.py runserver```

## MVP
- [ ] Access control
- [ ] Add a list of OLTs
- [ ] Save the list in a JSON file
- [ ] Monitor OLTs state:
  - [ ] UP, UNBLOCKED
    - [ ] OLT is up and unblocked
  - [ ] UP, PENDING
    - [ ] OLT is up and waiting to be unblocked
  - [ ] DOWN, COUNTING
    - [ ] OLT is down in a short period of time
  - [ ] DOWN, WAITING
    - [ ] OLT is down for some time and is waiting to come up
- [ ] Access OLT
  - [ ] Scrap Boards and versions
  - [ ] Monitor
  - [ ] Unblock
- [ ] LOG
- [ ] Multiplatform
- [ ] System-tray/daemon
- [ ] Open releases 

## License
MIT © HenrikBaltazar

## Author
Made by Henrik Baltazar

[![Linkedin Badge](https://img.shields.io/badge/-Henrik-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/henrik-baltazar-163923127/)](https://www.linkedin.com/in/henrik-baltazar-163923127/) 