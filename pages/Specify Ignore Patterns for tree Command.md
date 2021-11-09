- We can just simply provide all the patterns to the `-I` argument, separated by `|`. From the manpage:
  ```
  -P pattern
        List  only  those files that match the wild-card pattern.  Note:
        you must use the -a option to also consider those  files  begin‐
        ning  with a dot `.' for matching.  Valid wildcard operators are
        `*' (any zero or more characters), `?' (any  single  character),
        `[...]'  (any single character listed between brackets (optional
        - (dash) for character  range  may  be  used:  ex:  [A-Z]),  and
        `[^...]'  (any  single character not listed in brackets) and `|'
        separates alternate patterns.
  
  -I pattern
        Do not list those files that match the wild-card pattern.
  ```
- Example
  ```bash
  $ tree -I 'test*|docs|bin|lib'
  ```
- References
	- [How do we specify multiple ignore patterns for `tree` command? | StackExchange](https://unix.stackexchange.com/questions/47805/how-do-we-specify-multiple-ignore-patterns-for-tree-command)