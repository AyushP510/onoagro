# onoagro
A Goverment Of India Recognised and Certified APEDA Supplier

## Branches explained
* develop - This is the branch with running code. Any new feature to be added must be merged into this branch by raising a pull request.
For eg, If a new feature of adding a button is required on the main page. Follow these steps:
  * Create a branch out of develop having name feature/button and commit your changes
  * Once tested, raise a pull request to merge the changes from feature/button to develop
  * Once approved, the pull request can be merged and feature/button branch can be deleted

* release/x.x.x - This is the branch cut out of develop for a particular release(deployment). NO Code is to be merged in these branches.

* main - This is the branch with 2nd last successfully deployed code
