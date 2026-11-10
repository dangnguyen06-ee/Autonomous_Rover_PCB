# PCB folder guide

Open `Autonomous_Rover.kicad_pro` in KiCad to work on this project.

## Active design files — project root

- `Autonomous_Rover.kicad_pro`: project settings.
- `Autonomous_Rover.kicad_pcb`: routed board.
- `Autonomous_Rover.kicad_sch`: main schematic.
- `Input.kicad_sch`, `Output.kicad_sch`, `Power.kicad_sch`: schematic sheets. Keep these beside the main schematic.
- `Autonomous_Rover.round-tracks-config`: plugin settings.

## Manufacturing exports

`manufacturing/2026-11-09/gerbers/` contains the Gerbers exported on November 9, 2026, moved here without altering their contents.

No drill files were present when this folder was organized. Generate the Excellon drill files into this same directory before packaging the export. This folder is not a verified production release.

For future exports, set the KiCad Plot output directory to `manufacturing/YYYY-MM-DD/gerbers/` (replace the date). Use the same directory for drill files. Put the upload ZIP one level above `gerbers/` and export again after any design change.

## KiCad and repository housekeeping

- `.git`, `.gitignore`, `.gitattributes`: version-control data and settings.
- `.history`: existing local history; preserved.
- `.kicad_prl` and `~*.lck`: KiCad local settings and open-editor locks; leave them managed by KiCad.

No design files, backups, or repository history were deleted during organization.
