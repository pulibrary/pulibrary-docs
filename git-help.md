# Systems' Git Reference

## How to Contribute Code to github/pulibrary (for members)

1. Clone the repository<br>
  ```$ git clone https://github.com/pulibrary/ib.git /path/to/workspace/ib ```
1. Create a development branch (if fixing issue#, use that for branch name)<br>
  ```$ git checkout -b iss53```<br>
  _Switched to a new branch "iss53"_
1. Make changes
1. Add (aka, "stage") and Commit changes<br>
  ```$ git add . ```<br>
  ```$ git commit -m "write what you did..." ```
1. Push to origin<br>
  ```$ git push origin iss53 ```
1. Submit Pull Request through GitHub<br>
   ![Git-pull screenshot](https://github.s3.amazonaws.com/docs/pull-request-1.jpg)
1. After pull request has been accepted and merged, start back at the "trunk"<br>
   ```$ git checkout master```<br>
   _Switched to branch "master"_<br>
   ```$ git pull origin master```
  
## Collaboration with non-members of github/pulibrary
Please follow the instructions here for forking and merging:
https://help.github.com/articles/using-pull-requests