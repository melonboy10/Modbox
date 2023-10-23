# Modbox

Free opensource mod pack creator website

inspired by modrinth


I still have no clue ho I am going to do the backend infrastructure because I need auth, a database for modpacks tomls, somewhere to run packwiz (if it is possible to run it as a Go library then making a Go backend would be nice), and host.

Auth:
- Sign in with GitHub
- User ID in database

Database:
- Planetscale
- listfile for packwiz