# Space Station 14 Fork Database

Ye olde SS13 is almost impossible to learn anything interesting about. The large majority of early codebases from this time are gone, as they were not archived and mostly predate GitHub.

This repository serves three main purposes:
- Archival of information about SS14 servers from the very start such that it does not decay over time significantly.
- A central way for fork hosts to host information about themselves outside of their hub entry or game server.
- For the future, to provide an easy way to see fork lineage and generate a funny little graph for it.

This repository's directory structure intends to mirrors the fork tree of SS14--starting at mainline Wizard's Den SS14 and branching from there.

## Server Entry Structure

A server entry should look like this:

```
- ParentForkName
    - Children
        - YourServerName
            - README.md (copied from TEMPLATE.md)
            - logo.png (if applicable, no dimension restrictions)
            - Children (if applicable)
```

Folders and file names should not contain any spaces.

## Contributing

If you'd like to see your server listed here, feel free to make a PR. If you're unable to make a PR, contact me at `mirrorcult#9528` on Discord and I can create an entry for you.

If you want to otherwise make additions or changes, feel free to do so as well but please list sources properly.

Other guidelines:
- Folders and file names should not contain any spaces.
- All names/referents to particular people should be wrapped in backticks and prepended with `GH@` for 'github username' or `DSC@` for 'discord tag'.
- Currently, only forks with custom content are considered for archival here.
