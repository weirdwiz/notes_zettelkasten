---
tags:
  - makefile  

---
the targets in makefile are exectued from the top, so if there are no arguments then it'll run the topmost target.

```make

target: filename filename ..
	command
	
```

the file names mentioned in the target tell the compiler to execute the target again when the file content changes. **These are prerequisite for the target.**

---
### See Also
- [[202009230859 Automatic Variables]]

