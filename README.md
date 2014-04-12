# Table Prefixes for entities

Prepends configurable table prefixes to entity table names. 

## install via composer

```json

	"require": {
		"avanzu/sf-doctrine-prefix-bundle": "dev-master"
	}
	
```

## configure prefix

```yaml
	# app/config/config.yml
	
	avanzu_doctrine_prefix:
		prefix: my_table_prefix # defaults to empty string

```


