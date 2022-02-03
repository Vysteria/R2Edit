# R2Edit

A tool to build maps out of props in the Titanfall mod, Northstar.

# Instuctions

1. Install Northstar
2. Download this program
3. [Get the prop spawner tool](https://github.com/Vysteria/TitanfallMapEditor)
4. Enable cheats (sv_cheats 1)
5. Give your self the editor (give mp_weapon_editor)
6. Place objects
7. Copy the log from R2Northstar/logs when you want to save
8. Paste the logs in to a text file and save it
9. Run `main.py` and specify the input and output files to use
   1. For example, `python3 main.py ../examples/sample1.txt ../examples/out1.nut` will parse the included sample1 file
   2. If `python3 ...` doesn't work, you may need to install [Python](https://www.python.org/downloads/), or run it as `python ...`
10. Copy the contents of the output file to the bottom of `NorthStar.CustomServers/mod/scripts/vscripts/mp/(map of choice)`
11. Launch the map and you'll see your props

(Tutorial video soon) 

Join the official Discord server for [Northstar](https://discord.gg/northstar)
