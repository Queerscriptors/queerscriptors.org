Adding new projects:

Each project is in it's own folder under contents/, like butterflysoup/, under that is then placed a file named contents.lr with this:

```
sort_key: X
---
type: true
---
title: TITLE
...
body: BODY
```

The sort\_key is a number signifying the projects placement from top (lower numbers) to bottom (higher numbers), it currently starts at 0 with Lucah BOAD (xx: should inverse sort such that adding new projects is easier?).  
Type is a bool (that is, true or false) signifying if it the images should be on the left (true) or on the right (false).  
Title is.. the title, this should (probably) be the name of the game.  
Body is the small text under the title

---
