import os 
import subprocess 
#############################

fline=subprocess.getoutput(f"head -1 livetime 2>/dev/null")
		
if fline != "#!/bin/bash":
   	 os.system(f"sed -i '1 i #!/bin/bash' livetime")
else:
   	 print(".")

subprocess.getoutput(f"chmod +x livetime")
subprocess.getoutput(f"sudo cp livetime /usr/bin/")
		
print("done")
