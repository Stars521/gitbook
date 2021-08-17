> 分组：（分组提取其他字段）

```mysql
SELECT
	GROUP_CONCAT( CARD_NUMBER, ORGANIZATION_NUMBER ) 
FROM
	card_authorization_info 
GROUP BY
	PRIMARY_CUSTOMER_ID 
	LIMIT 1
```

> 使用一条sql删除多条数据

```mysql
DELETE 
FROM
	表名 
WHERE
	字段 IN ( 数据, 数据, 数据 );DELETE 
FROM
	表名 
WHERE
	字段 IN ( 数据, 数据, 数据 );
```

