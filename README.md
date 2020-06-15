# taobao itemcats 淘宝全部类目

更新日期 2020-06-15

mysql数据表
```
CREATE TABLE `taobao_itemcats` (
  `cid` int(11) NOT NULL,
  `parent_cid` int(11) NOT NULL DEFAULT '0',
  `name` varchar(200) COLLATE utf8mb4_unicode_ci NOT NULL DEFAULT '',
  `is_parent` tinyint(1) NOT NULL DEFAULT '0',
  PRIMARY KEY (`cid`)
) ENGINE=MyISAM DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_unicode_ci;
```