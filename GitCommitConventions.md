# Git Commit Conventions

| Commit Sufix        | Description                                           | Examples                                                            |
|:--------------------|:------------------------------------------------------|:--------------------------------------------------------------------|
| [ chore ]           | regular development flow commit                       | chore: add ApplicationDbContext                                     |
| [ test ]            | regular test flow commit                              | test: ensure that GlobalFunctionsClass's: <br/> SetSecurityClaims_UserExists_SetsSecurityClaims |
| [ ref ]             | refactoring                                           | ref: replace IEnumerable to ICollection in Customer domain model    |
| [ fix ]             | a bug fixing commit                                   | fix: Activator parameter in the CityLocationMapper                  |
| [ config ]          | config commit                                         | config: FolderProfile.pubxml for AuthServer                         |
| [ docs ]            | add summary to IdentityService class                  | docs: add summary to IdentityService class                          |
| [ cln ]             | remove redundants, usless namespaces, code formating. | cln: UnzipperTests                                                  |
| [ !chore ]          | regular development flow commit with deleting (consider commit revert) | ! chore: remove security flag claims seeding       |
| [ !test ]           | regular test flow commit with deleting (consider commit revert)        | ! test: delete ApplicationDbContextTests           |

