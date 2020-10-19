## Example of git rebase

### Step 1

Initial commit - ветка master - 2fbbe67
b1.1 - ветка b1 - 85eac43
master after b1.1 - ветка мастер b505f18
b1.2 - ветка b1 - 2d7d4ea
+1 - ветка master - 8dcef6c

### Step 2

```
git checkout master && git log
8dcef6c "+1"
b505f18 "master after b1.1"
2fbbe67 "Initial commit"
```

```
git checkout branch && git log
2d7d4ea "b1.2"
85eac43 "b1.1"
2fbbe67 "Initial commit"
```


