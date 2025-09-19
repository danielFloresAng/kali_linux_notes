<!-- Terminal shor-cuts -->
  - New tab -> shift + control + T
  - Rename tab -> alt + shift + S
  - Move tab -> shift + alt + < / >

<!-- Commands -->
  - ls -l -> File details
  - ls -la -> File details and hiden objects
  - whoami -> Shows user
  - su -> Change user
  - -h -> Shows commands and helpful info about apps or programs. Should be tipe after a tool, Ej.: nmap -h
  - man -> Shows the manual of an app or tool, ej.: man nmap
  - which -> shows the path for a binary (app) ej.: which fireforx
  - find -> find a file
  - sudo -> Super user permissons, we could use this command when need acces to a super user files
  - cat -> shows the content of a file      
  - grep -> Filter the files that we need while give it a keyword to find it. Is's case sensitive. We can use grep command to find keywords in a string, text, script, etc.
      <Ej.: ls -la | grep file-name>
      <Ej.:  cat file.txt | grep -n keyword_to_find>
  - ifconfig -> Shows the network info of our machine
  - ping -> Shows de data that we receive and send from the ip that we did type.
      <Ej.: ping google.com>
      <Ej.: ping 127.00.29.38>
  - netstat -> It shows the nets status
  - nslookup -> Tell us the ip of a web addres or viceversa
      <Ej.: nslookup google.com>
  - sudo adduser 'new-user' -> Creates a new user from the terminal, we can give it privileges
  - id -> Shows the identifiers and groups that our user belongs to
  - w -> Tell us who is connected to our machine and the actions of those that are conected
  - ps -> Show the procces and actions that our system executes 
  - jobs -> Shows the tasks that are paused on the actual user
  - fg -> Start the task selected
  - kill PID -> Quit the task correspondent to the PID 
  - kill -9 PID -> Force quit the task correspondent to the PID 
  - pkill TASK_TO_QUIT -> Quit the task by the name of the proces, not the PID
  - chmod -> edit the levels of acces to a binary or directory. It could be with 3 digits after the commands that indicates the level of acces of the user, the groups and others. 
    <Ej.: chmod 764>
  - chown -> change the user or group of a binary or directory
  

<!-- Terminal commands actions -->
  - ctrl + c -> Ends the actual tastk
  - ctrl + z -> Pause the actual task

<!-- Terminal atributes:  -->
  - -i -> Ignores the case sensitive
  - -n -> It refers a name