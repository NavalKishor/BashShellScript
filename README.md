# BashShellScript
**[pre-commit](https://github.com/NavalKishor/BashShellScript/blob/master/pre-commit)**
:pre-commit is the easy way to look for pattern of string in `grep` and stop the user to commit.
<br> Just add the specific key string in this file and call the `lookTodie` method like
> `MATCH='Naval'` <br>
> `lookTodie "$diffAdded" "$MATCH"` <br>

that's it and we can prevent accidental commit of ***Naval*** any time.
**We can use regular Expression as well like**
**`MATCH=“New[abc]”`**

**Keep in mind after downloading or saving this scripts** 
1.  "pre-commit" file place in the .git/hooks/ folder
2.  also give execution permission for the file using <br>
`chmod +x .git/hooks/pre-commit` <br>
3. verify using <br>
`ls -l .git/hooks/pre-commit`<br>
> -rwxr-xr-x@ 1 naval  603018132  2594 Dec 28 02:38 .git/hooks/pre-commit<br>

you are all set.


