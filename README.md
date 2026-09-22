# Relation map

Directed graph of the Terpkit block notes. An arrow means **depends on**. The text on a link is the medium that crosses it: a Measurement Set, an h5parm, FITS, a parset, or a command.

**Open:** https://jomdh.github.io/lofar_data_analysis/

The header switches two views.

- **Graph** is this page. An arrow means depends on.
- **Stack** is [stack.html](https://jomdh.github.io/lofar_data_analysis/stack.html). One bar per program across the stages.

Three stops on the graph:

- **Project.** One node per tool. `wsclean` and `ext.wsclean` are the same node, and the `ext.` prefix is dropped. A library that has no graph of its own stays a gold node, named without that prefix.
- **Group.** `linc.calibrator.pa` folds to `linc.calibrator`. External nodes stay put.
- **Code.** Every id, as written in the block graph.

Blue nodes are inside a tool. Gold nodes are external. Click a folded node to list the ids it contains.

The source graphs are the `blocks/<tool>/graph.json` files in the terpkit tree.
