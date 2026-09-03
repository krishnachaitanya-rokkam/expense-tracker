V13 Menu Root Fix

Root cause fixed: nav() was rebuilding the menu after sign-out.
Now nav() and render() refuse to render app navigation/content when
cloudUser is absent. Logout also clears the generated menu immediately.

Deploy all files to the same GitHub Pages repository.
