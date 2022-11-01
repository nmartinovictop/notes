Creating Tables:

```SQL
create table "tablename"
("column1" "data type" 
         [constraint],
 "column2" "data type" 
         [constraint],
 "column3" "data type" 
        [constraint]);
 [ ] = optional
```

Inserting Data:

```SQL
insert into "tablename"
 (first_column,...last_column)
  values (first_value,...last_value),
  (first_value,...last_value);
```

Updating Data

```SQL
update "tablename"
set "columnname" = 
    "newvalue"
 [,"nextcolumn" = 
   "newvalue2"...]
where "columnname" 
  OPERATOR "value" 
 [and|or "column" 
  OPERATOR "value"];

 [] = optional
```

Deleting Data

```SQL
delete from "tablename"

where "columnname"
OPERATOR "value"
[and|or "column"
OPERATOR "value"];

[ ] = optional
```

Drop Table

```SQL
drop table "tablename"

```
