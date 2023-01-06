# ups
path360: error: Error during autofill! This means it is a bug in Ink/Stitch.

Ink/Stitch Version: thisandthat01 (windows)

Traceback (most recent call last):
  File "lib\elements\fill_stitch.py", line 560, in to_stitch_groups
  File "lib\elements\fill_stitch.py", line 594, in do_underlay
  File "lib\debug.py", line 133, in decorated
  File "lib\stitches\auto_fill.py", line 75, in auto_fill
  File "lib\debug.py", line 133, in decorated
  File "lib\stitches\auto_fill.py", line 630, in path_to_stitches
  File "lib\stitches\auto_fill.py", line 591, in travel
  File "networkx\algorithms\shortest_paths\generic.py", line 167, in shortest_path
  File "networkx\algorithms\shortest_paths\weighted.py", line 2374, in bidirectional_dijkstra
networkx.exception.NetworkXNoPath: No path between (321.49748977890226, 396.7999391941083) and (314.6456692913386, 400.78378017574147).
