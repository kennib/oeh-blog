# Test
This is a test blog page

```elm
type Blog = NoBlog | GoodBlog

read : Blog -> Int
read blog = case blog of
	NoBlog -> 0
	GoodBlog -> 9001
```
