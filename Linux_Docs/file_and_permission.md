<h2>This section follow up with  file and directories permission.</h2>

<h4>1. ls -l:   This will display all the listed file/dir permission</h4>
             <ul>eg: ls -l
             <p>output: -rw-rw-r-- 1 deepak deepak 115 Aug 30 02:23 deepak.txt <br>here '-rw-rw-r--' are the permission granted for file.</p>
             <b>o = other</b><br>
             <b>u= user</b><br>
             <b>g= group</b>

  </ul>
  


<h4>2. change file/dir permisson: chmod [option/permisson] filename</h4>
              <ul><p>To change file/dir permission ,it can be done by following commands.</p>
              <p>eg : chmod o+xwr deepak.txt.</p>
                    + = adding permission<br>
                    - = removing permission </ul>
                    


<h4>3. Change file owner and group.</h4>
<ul><p>This command will change file owner and group.</p>
commands: chown [user:group] filename<br>
This commands can also change user and group using ":" colon in between user and group<br>
<ul>
  <li>eg: chown deepak:deepkagroup file2.txt<br></li>
  <li>This will modify the user to 'deepak' and group to'deepakgroup' for file2.txt</li>
</ul> 
</ul>


<h4>4. This will used to change group permission for file or dir.</h4>
<ul>
  <p>commands: chgrp groupname filename</p>
  <li>eg: chgrp deepakgroup file3.txt</li>
  <li>This will update group to new group.</li>
</ul>



          
          
              

               
   
     
             

   
  
