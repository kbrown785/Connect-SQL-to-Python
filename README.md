# Connect-SQL-to-Python

## Getting Started
1. Get access to the ec-app10.test.econ.census.gov server.
2. Once you get access
   1. Go to Windows PowerShell, type `ssh -L 1234:localhost:1234 JBID@ec-app10.test.econ.census.gov`, and push Enter.
      1. The "1234 should be any 4 digits that don't give you an error.
      2. JBID = your JBID
   2. Enter network password and push "Enter". It won't show you typing.
   3. Type `source /apps/anaconda/bin/activate cfsenv` and push Enter.
   4. Type `jupyter lab --port=1234` and push Enter.
   5. You will see something that says, "Or copy and paste one of these URLs:" and it will list 2 URLs. I tried copy and pasting the first one into my browser and JupyterLab opened.
   6. You will see a list of folders on the left-hand side of the screen. You can keep your files wherever you want. I'm going to double-click on "Documents".
   7. Click on my "sql_to_python.ipynb" file in GitHub and download it. In my case, I then drag-and-dropped it into "Documents" and double-clicked it.
   8. There are 2 "cells" of code. Update the user and password in the first cell, then click the little triangle icon above. I recommend studying the code so that you know what it should do if it's working properly. Then, update the user and password in the 2nd cell and run the code.
   9. File -> Shut Down 
      
## Help
You can get help from me if you need it!
