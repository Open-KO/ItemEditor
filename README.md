> [!NOTE]
> This tool is unfinished and currently acts more as an item *viewer* than an *editor*.

# ItemEditor

This tool's intended purpose is to cut down the number of jumps between database, TBL & client-aside asset file edits which are needed to add or update items in the game.

In its current state, this tool indexes, loads and renders item meshes from the provided `Item_org.tbl` and your database (using ODBC - DSN: `KN_online`, user: `knight`, password: `knight`).

Item meshes must exist in `Item/` (relative to the ItemEditor's working directory).

This tool was written by [@srmeier](https://github.com/srmeier) and was originally part of the [main OpenKO repository](https://github.com/Open-KO/KnightOnline).
