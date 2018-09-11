# EditString  
> Dale, Joyce, Weems (4th) p154 #30  

Using the ArrayBoundedStack class, create an application EditString that
prompts the user for a string and then repeatedly prompts the user for changes to
the string, until the user enters an X, indicating the end of changes. Legal change
operations are:  

    U — make all letters uppercase  
  	L — make all letters lowercase  
  	R — reverse the string  
  	C a b — change all occurrences of 'a' to 'b'  
  	Z — undo the most recent change  
  	X — end changes and exit  
    
You may assume a “friendly user,” that is, the user will not enter anything illegal. When
the user is finished the resultant string is printed. For example, if the user enters:

    All dogs go to heaven
    U
    R
    Z
    C O A
    C A t
    Z
    
the output from the program will be  

    “ALL DAGS GA TA HEAVEN”
