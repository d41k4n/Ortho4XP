# Ortho4XP - Unofficial Simheaven Hack
Ortho4XP is a scenery generator for the X-Plane flight simulator, written by _**Oscar Pilote**_

**Please be aware that THIS IS NOT THE OFFICIAL Ortho4XP**.

This version/branch contains modifications done by [PilotBalu](http://forums.x-plane.org/index.php?/profile/227571-pilotbalu/) based on release v1.20b with the following additional features:
- line 0193: define max number of vertices
- line 2763 - 2791: loop to increase curvature_tol step by step to get best results (starting at 0.2, increasing until # of tris is optimal)
- line 2903: file names without service and zoomlevel, allows mixing of different services (some tiles may be generated from images from different services - this makes it easier)
- line 4553: also clean temp files for OSM and MESH (temporary .osm and .mesh files will be deleted at the end of the run)

Published via the following comment on the (german) Aerosoft forum:
http://forum.aerosoft.com/index.php?/topic/101230-ortho4xp/&do=findComment&comment=801435

**It may or may not work** for you, as this is all a work in progress for now.

A few resources for the original Ortho4XP :
- Forum : http://forums.x-plane.org/index.php?/forums/forum/322-ortho4xp/
- Discord Community : https://discord.gg/78nD2
- Original Ortho4XP git repository : https://github.com/oscarpilote/Ortho4XP
- Original Ortho4XP dropbox : https://www.dropbox.com/sh/cjjwu92mausoh04/AACt-QzgMRwKDL392K_Ux3cPa?dl=0