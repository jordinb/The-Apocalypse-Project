
## Conversion batch test route

Use this route after restarting the resource. Check that roads, sidewalks, base game geometry, and new props stream together without flickering or duplicate physics.

1. Stuart Apocalypse: `436, -611, 28` and `412, -683, 28`
2. Abandoned Road: `-1172, -300, 37`
3. Post-Apocalypse Vinewood: `288, 168, 103`
4. Apocalypse Safebase: `-393, -2258, 10`
5. Tobaklo Apocalypse: `-44, -1080, 31`
6. Safezones: desert `1550, 3600, 37`; west coast `-2750, 1460, 104`; Paleto `1480, 6370, 24`; airport `530, -2000, 27`
7. After Us Hospital: `335, -1426, 31`

Static validation complete: all streamed YMAPs were read by CodeWalker, flags/extents recalculated, and newly created maps reloaded successfully. Run the route once in FiveM before release to catch visual LOD issues that only show in the client renderer.
