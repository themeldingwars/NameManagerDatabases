# NameManagerDatabases
Database files for use with [Firefall DISASM Name Manager](https://github.com/themeldingwars/Firefall-DISASM-Name-Manager)

## How to Contribute
When working on reverse engineering the client, you can store subroutine names within the database files used by [Firefall DISASM Name Manager](https://github.com/themeldingwars/Firefall-DISASM-Name-Manager). These can then be committed back into this repository for users to add to their own local databases.

### Allowed Characters In Names
The following is a list of characters approved for names that have been confirmed to be handled gracefully in all supported applications.

`.:_0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz`

Pull Requests will not be merged that contain characters outside of the above list unless ample reasoning is provided for why the list should be expanded.

### Duplicate Name Handling
When duplicate names occur, they should be handled by appending `_#` to the end of the name. Where the `#` is incremented for each additional occurrence.

### For Public Users
1. Verify your local database includes the latest version of the matching Client Version database on this repo.
  * You can download the latest version from here and import into yours to update it.
2. Save your database in Firefall DISASM Name Manager.
  * The database should be named using the default naming scheme of `FF_DISASM_V{ClientVersion}.json`.
3. Create a Pull Request for the database to be placed into the proper directory.
  * For example, Client Version beta-1962 would be located in `production\beta\FF_DISASM_V1962.json`.

NOTE: This tool has basic [deduplication supported](https://github.com/themeldingwars/Firefall-DISASM-Name-Manager#deduplication). However, depending on your data you may still need to handle duplicates/edits to existing items manually.
