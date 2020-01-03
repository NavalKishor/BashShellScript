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



**[gproxy](https://github.com/NavalKishor/BashShellScript/blob/master/gproxy)**
:gproxy is the easy way to enable or disable the proxy.
<br>Change the permission of file using this command
<br>Download this(gproxy) file and copy the file in `$HOME/bin` use the below commands<br>
> `mkdir $HOME/bin`<br>
> `cp gproxy $HOME/bin/gproxy`<br>
> `chmod +x $HOME/bin/gproxy`<br>
Edit this changes as per your need
<br> Just edit these keywords
<br>YourUsername:`UserName`
<br>YourIPAddress:`127.0.0.1`
<br>YourPortNo:`8080`
<br>and from terminal just type<br>
> `gproxy`  
<br>and hit the [Enter/return key]

you are all set.


