---
tags: 
  - makefile  
---
# Creating OBJS from SRCS

`OBJS = $(SRCS:.c=.o)`

This means replace all `.c` with `.o` from the `SRCS` variable

---
### See Also
- [[[OBJS]]]

