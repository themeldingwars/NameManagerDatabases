# NameManagerDatabases
Database files for use with [Firefall DISAM Name Manager](https://github.com/themeldingwars/Firefall-DISAM-Name-Manager)

## How to Contribute
When working on reverse engineering the client, you can store subroutine names within the database files used by [Firefall DISAM Name Manager](https://github.com/themeldingwars/Firefall-DISAM-Name-Manager). These can then be committed back into this repository for users to add to their own local databases.

### For Public Users
1. Verify your local database includes the latest version of the matching Client Version database on this repo.
  * You can download the latest version from here and import into yours to update it.
2. Save your database in Firefall DISAM Name Manager.
  * The database should be named using the default naming scheme of `FF_DISAM_V{ClientVersion}.json`.
3. Create a Pull Request for the database to be placed into the proper directory.
  * For example, Client Version beta-1962 would be located in `production\beta\FF_DISAM_V1962.json`.
