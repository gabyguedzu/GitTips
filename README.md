# GitTips
:octocat:

> is _indicated_ for those who already have a knowledge base on the **GIT versioning** tool

#### Branchs

> branch master, it is recommended to leave only the code finalized, tested and ready for production.

##### Nomenclature suggestion

###### Features

* feature_78364-overdraft
* feature/overdraft

###### Bugfix

* fix_78364-overdraft
* fix/overdeaft



#### Git flow | Branchs

![](img/gitflow.png)

> https://git-school.github.io/visualizing-git/ - test and play

Example:

![](img/visualbranches.png)

___



#### About commit

> If you're in charge of English and your team too, then check it out, commit everything in English.

> If you do not understand very well. Please commit in Portuguese.

- Commit

  * It was not marked to commit, the add was not done, run command: ```git checkout -- arquivo```

  * Undo a change that was marked to commit, done the add, run command: ```git reset HEAD arquivo```

  * Undo a change that has been marked to commit and has been committed!

    ​		run command: ```git log```

    ​		to see the hash of the commit, then, run command: ```git revert 49ghg434hghg434398sdhs```

    this will create a new commit, undoing the revert

- Stash
  * to save modifications to a temporary location, run command: ```git stash```
  * list saved stashs, run command: ```git stash list```
  * resume a specific saved stash, run command: ```git stash apply INDICE_DO_STASH```
  * delete stash, run command: ```git drop stash```
  * apply and remove stash, run command: ```git stash pop```
  
- Uniting commits

  * Let's rebase, run command: ```git rebase -i HEAD~3```
  * Will open the default editor of your PC, in my case the VI, select the commit to be the pick, add s in the rest.

  Here's an example from the following image:

  ![](img/rebasei.png)



* Getting a specific commit (otherwise branch)  and bringing to current branch

  * run command: ```git cherry-pick hash_do_commit```

  

Example:

![](img/cherrypick.png)



