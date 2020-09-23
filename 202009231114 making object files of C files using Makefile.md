Tags: #makefile 
From: [[202009230859 $@, etc]]

---
If we have a lot of `.c` files in the directory, we could write a target for in the Makefile to compile them into `.o` files. Without explicitly executing their target.

example :
```make
%.o : %.c
	$(CC) -c $< -o $@

```

 This rule is created implicitly, if we use any `.o` flie in the some rule. The make file will look for a rule to get that file.

---
### See Also
- [[202009230859 $@, etc]]
- [[202009231119 $% symbol]]