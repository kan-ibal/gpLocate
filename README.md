# gpLocate
Sailfish GUI for plocate
- needs plocate installed on sailfish device
- alpha state
- self updatable user db or system db
- open dir (needs harbour-file-browser)
- open file (xdg-open)
- plocate services must be started before using this application.
   devel-su systemctl --user start plocate-updatedb-user
   devel-su systemctl start plocate-updatedb