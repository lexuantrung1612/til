# Support Vietnamese, Emoji
- utf8 only use 3 bytes => Use utf8bm4 encoding and collation

```sql
> ALTER TABLE `table_name` MODIFY `column_name` TEXT CHARACTER SET utf8mb4 COLLATE utf8mb4_bin
> ALTER TABLE `table_name` CONVERT TO CHARACTER SET utf8mb4 COLLATE utf8mb4_bin

```

```migration
> def change
    execute 'ALTER TABLE `table_name` CONVERT TO CHARACTER SET utf8mb4 COLLATE utf8mb4_bin'
  end
```
