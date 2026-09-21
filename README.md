# Relation map

Directed graph of the Terpkit block notes. An arrow means **depends on**. The text on a link is the medium that crosses it: a Measurement Set, an h5parm, FITS, a parset, or a command.

**Open:** https://jomdh.github.io/lofar_data_analysis/

Three stops:

- **Project.** One node per tool. Shared libraries stay `ext.*` and do not fold into a tool.
- **Group.** `linc.calibrator.pa` folds to `linc.calibrator`. External nodes stay put.
- **Code.** Every id, as written in the block graph.

Blue nodes are inside a tool. Gold nodes are external. Click a folded node to list the ids it contains.

The source graphs are the `blocks/<tool>/graph.json` files in the terpkit tree.
