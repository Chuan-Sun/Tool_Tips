#1级节点 

[菜鸟教程](https://www.runoob.com/sql/sql-tutorial.html)

## 常用命令
`SELECT`
```SQL
SELECT col, col FROM tab LIMIT 10;
SELECT * FROM tab;
SELECT DISTINCT col FROM tab;
```

`WHERE`
```SQL
SELECT col FROM tab WHERE col='a';
```

`ORDER BY`
```SQL
SELECT col FROM tab ORDER BY col, col ASC|DESC;
```

`JOIN`
```SQL
SELECT a.col FROM tab a JOIN tab b ON a.key = b.key
```

`NULL`
```SQL
SELECT col FROM tab WHERE col IS NULL
SELECT col FROM tab WHERE col IS NOT NULL
```

`MAX`
```SQL
SELECT MAX(col) FROM tab
```