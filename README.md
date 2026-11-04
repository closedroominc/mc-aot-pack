# Closed Room INC. client pack

Static mirror of the MC-Manager client sync data, served through GitHub so players
do not need access to the server's dashboard to install or update mods.

Players run the one-line command posted in Discord (PowerShell or cmd). It updates the
existing "Closed Room INC." launcher entries (SKLauncher / TLauncher) in place and never
creates duplicate copies. Mods download from Modrinth, checked against the hashes in
`client/aot/sync.txt`.

Regenerate and publish from the host with `publish-pack.ps1` in the server folder.
