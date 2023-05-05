# UndoGit
To undo the last commit from a remote git repository, you can use the following cmd that are wraped with >> <<
First, you can use the, >> git reset HEAD^ << command. This will undo the last commit locally.
Then you can use the, >> git push origin +HEAD << command to force push the local commit which was reverted to the remote git repository.
