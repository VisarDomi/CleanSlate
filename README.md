https://github.com/ck2plus/CleanSlate

### TODO:
#### change
```
any_child = {
	count < 2
	is_female = yes
}
```
#### into
```
NOT = {
	any_child = {
		count >= 2
		is_female = yes
	}
}
```
count < 2, demesne_size < 2, realm_size < 2 do not wor because of engine limitations.