# Git Commit Conventions

| Commit Sufix        | Description                                           | Examples                                                            |
|:--------------------|:------------------------------------------------------|:--------------------------------------------------------------------|
| [ chore ] - module/entity -          | regular development flow commit                       | [ chore ] - FooModule - add ApplicationDbContext                                     |
| [ test ] - module/entity -             | regular test flow commit                              | [ test ] - BarClass - ensure that GlobalFunctionsClass's: <br/> SetSecurityClaims_UserExists_SetsSecurityClaims |
| [ ref ] - module/entity -              | refactoring                                           | [ ref ] - replace IEnumerable to ICollection in Customer domain model    |
| [ fix ] - module/entity -              | a bug fixing commit                                   | [ fix ] - Activator parameter in the CityLocationMapper                  |
| [ config ] - module/entity -           | config commit                                         | [ config ] - DesktopClient - FolderProfile.pubxml for AuthServer                         |
| [ docs ] - module/entity -             | add summary to IdentityService class                  | [ docs ] - add summary to IdentityService class                          |
| [ cln ] - module/entity -              | remove redundants, usless namespaces, code formating. | [ cln ] - UnzipperTests                                                  |
| [ !chore ] - module/entity -           | regular development flow commit with deleting (consider commit revert) | [ !chore ] - WebApi - remove security flag claims seeding       |
| [ !test ] - module/entity -            | regular test flow commit with deleting (consider commit revert)        | [ !test ] - delete ApplicationDbContextTests           |

