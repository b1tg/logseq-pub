- https://github.com/jakogut/mlibc
	- things like:
	  ```c
	  char *strcat(char *dest, const char *src)
	  {
	  	char *dp = dest, *sp = (char *)src;
	  	while (*(dp+1)) dp++;
	  	while (*(sp+1)) *(dp++) = *(sp++);
	  	return dest;
	  }
	  ```
-