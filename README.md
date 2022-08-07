# onoagro
A Goverment Of India Recognised and Certified APEDA Supplier

## Running the application
There can be various way of running the application:
* Directly open index.html in any modern day browser (chrome, edge etc.)
* Use live-server from npm. To install, run `npm install -g live-server`. Once installed, simply use command `live-server`.
This will host the application at `127.0.0.1:8080`. You can also access it on any other device connected via the same private network using the PC's ip address on the network.
* Use http-server from npm. Very similar to live-server.
  
  ![image](https://user-images.githubusercontent.com/24705402/183280698-9ca9f701-a216-4511-85dc-fcf4e617e0a2.png)


## Branches explained
* develop - This is the branch with running code. Any new feature to be added must be merged into this branch by raising a pull request.
For eg, If a new feature of adding a button is required on the main page. Follow these steps:
  * Create a branch out of develop having name feature/button and commit your changes
  * Once tested, raise a pull request to merge the changes from feature/button to develop
  * Once approved, the pull request can be merged (Using Rebase & Merge option, DO NOT create merge commits) and feature/button branch can be deleted
    
    ![image](https://user-images.githubusercontent.com/24705402/183281773-f39b2eb9-bb96-4497-835e-8b416c72ea31.png)


* release/x.x.x - This is the branch cut out of develop for a particular release(deployment). NO Code is to be merged in these branches.

* main - This is the branch with 2nd last successfully deployed code
