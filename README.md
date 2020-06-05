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

##### Commit

It was not marked to commit, the add was not done: ```git checkout -- arquivo```

Undo a change that was marked to commit, done the add: ```git reset HEAD arquivo```

> Undo a change that has been marked to commit and has been committed!

```git log```

to see the hash of the commit, then: ```git revert 49ghg434hghg434398sdhs```

> this will create a new commit, undoing the revert

##### Stash





