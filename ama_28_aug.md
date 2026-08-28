# AMA - 28 Aug

## 1. Which command is used to check file permissions in decimal format?

Use:

```bash
stat -c "%a" filename
```

It displays the file permissions in numeric (octal) format, such as `644`.

## 2. What is atomicity?

Atomicity is an ACID property that means a transaction is completed completely or not executed at all. If any operation fails, the entire transaction is rolled back.

## 3. How can you change a Git commit message?

For the most recent commit, use:

```bash
git commit --amend -m "New commit message"
```

For an older commit, use interactive rebase:

```bash
git rebase -i HEAD~3
```

Then change `pick` to `reword` for the commit whose message you want to change.

## 4. How can you print the last 30 lines of a file?

Use:

```bash
tail -n 30 filename
```

## 5. What is Python?

Python is a high-level, interpreted, general-purpose programming language known for its simple and readable syntax.

## 6. What is `git revert`, and how is it used?

`git revert` is used to undo the changes of a previous commit by creating a new commit that reverses those changes.

Use:

```bash
git revert <commit-hash>
```

Unlike `git reset`, `git revert` keeps the existing commit history.

## 7. How can you copy data from a CSV file into an SQL table?

In PostgreSQL, use:

```sql
\copy table_name FROM 'file.csv' WITH (FORMAT csv, HEADER true);
```

It imports the data from the CSV file into the specified table.

## 8. How can you find hidden files larger than 10 MB in a directory?

Use:

```bash
find . -type f -name ".*" -size +10M
```

It finds hidden files larger than 10 MB in the current directory and its subdirectories.

## 9. How can you list files in reverse order?

Use:

```bash
ls -r
```

It lists files and directories in reverse alphabetical order.

For reverse order by modification time, use:

```bash
ls -ltr
```

## 10. Which command is used to find a word in a file?

Use:

```bash
grep -i "word" filename
```

`grep` searches for a specified word or pattern inside a file.

## 11. What is encapsulation?

Encapsulation is an OOP concept that bundles data and methods together inside a class and restricts direct access to the internal data.

## 12. What is the full form of `grep`?

`grep` stands for **Global Regular Expression Print**. It is used to search for matching text patterns in files.

## 13. What is SRP in SOLID?

SRP stands for **Single Responsibility Principle**. It says that a class should have only one responsibility or one reason to change.
