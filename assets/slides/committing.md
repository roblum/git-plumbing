### Committing files from Staging

`write-tree` creates a tree object with the current index file.

```sh
$ git write-tree
80865964295ae2f11d27383e5f9c0b58a8ef21da
$ git cat-file -p 80865964295ae2f11d27383e5f9c0b58a8ef21da

$ echo "first commit" | git commit-tree 80865964295ae2f11d27383e5f9c0b58a8ef21da
$ git cat-file -p 3a5a00a726b1710a9d50f8ad95aaa212c04739c0

$ git status
```

@[1-2]
@[3]
@[5-6]
@[8]
