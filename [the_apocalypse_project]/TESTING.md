# Regional test guide

Production startup uses one line:

ensure [the_apocalypse_project]

To isolate a crash, temporarily replace that line with exactly one regional resource. pocalypse-core starts automatically through the declared dependency.

ensure apocalypse-los-santos
ensure apocalypse-blaine
ensure apocalypse-infrastructure
ensure apocalypse-statewide
ensure apocalypse-interiors

Test one resource per restart. If one group is stable alone but crashes when paired with another, we can narrow the offending map pack without touching the rest of the project.