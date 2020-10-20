Tags: #makefile 
From: [[202009230835 Makefile for compiling kernel.img]]

---
if the example is 
```make

target: sourcefile1 sourcefile2
	command ....


```

in this case `$@` would amount to `target`,  `$<` would be `sourcefile1` and `$^` would be `sourcefile2`.


---
### See Also

