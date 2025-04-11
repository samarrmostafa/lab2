

##  How to delete branches

### Locally

```bash
git branch -d dev
git branch -d test
```

### Remotely

```bash
git push origin --delete dev
git push origin --delete test
```


---
```

---

 3. **Annotated tags vs Lightweight tags (for README.md):**


```
### Annotated vs Lightweight Tags

- **Annotated Tags**: Recommended for releases. Contains tagger name, email, date, and message. Stored as full objects in the Git database.
- **Lightweight Tags**: Like a bookmark to a commit. No extra metadata or message.
```

---

 4. **When to use Rebase (for README.md):**


```
### When to use Rebase

- To maintain a clean linear history.
- Before merging feature branches to avoid unnecessary merge commits.
- When collaborating, rebase before pushing to update local commits.
```

---
 5. **How to list tags? 


```
### How to list tags?

To list all tags:
git tag

To search tags with a pattern:
git tag -l "v1.*"
```

---

 6. **How to delete tag locally and remotely? 

```
### How to delete a tag

Delete locally:
git tag -d v1.7

Delete remotely:
git push origin --delete tag v1.7
```

---
(orange.png)

 <img src="orange.png" alt="orange photo" width="300" />