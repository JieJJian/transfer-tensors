# Third-party data rights

The software license in `LICENSE-CODE` is deliberately scoped to code. It does not relicense the upstream data or grant permission over third-party records, player information, database contents, or the original research paper.

| Material | Source | What is verified |
|---|---|---|
| `raw_sources/d2ski.zip` | Antipov, `football-transfers-data`, revision 88ffbc2 | Exact archive hash matches the frozen source lock; README credits Transfermarkt; no license/permission file found in the archive |
| `raw_sources/ewenme.zip` | Henderson, `transfers`, revision b531325 | Exact archive hash matches the frozen source lock; README credits Transfermarkt and mentions its terms; no license/permission file found in the archive |
| `tensor_data/v1/` | Derived by this project's builder | Exact frozen processed data and lineage included; upstream redistribution basis has not been established |
| Model software and scripts | This project's CPU adaptation of the Jian–Schein method | Code-only MIT license supplied; upstream method credited |

Both source archives were inspected for LICENSE, COPYING, CITATION, and notice files. None was found. The source README text is retained inside each unmodified archive. No data license or DOI has been inferred from public download availability, the existence of a GitHub repository, or a license attached to another repository by the same author.

This local package includes the data needed for replication but **is not yet a cleared public data release**. Record any applicable permission/license and its scope before publication. The current audit does not conclude that publication is prohibited; it records an unresolved evidentiary item. The author may already have permission not present in these files.
