# Hillel-DevOps
Public repository for DevOps Hillel

Description of GitFlow:
- main (master): The branch where the most stable changes that go in the release go. Only changes from the release and hotfix branches are merged into the master branch.
- hotfix: Temporary hotfix branches are created to fix critical issues in the release version. The branch departs from master and, upon completion of bug fixes, it is merged back. The branch itself is then deleted, and the merge commit in master is tagged with the new version.
- develop: Stable code for new features and bug fixes gets into this branch.