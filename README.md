# Description
This simple python scripts checks your password for security threats using https://haveibeenpwned.com/ API  
 
## Project Overview:  
* Importing Libraries
* Passing Password as a argument through **sys.argv** 
* Converting the password to **Secure Hash Algorithm 1** using **hashlib**
* Getting the hashed response from the API and matching it on first 5 characters to prevent password check over API server  
* Matching the password and getting the count (times password is compromised)
* Returning a string output for multiple password arguments

## Libraries Used
* requests
* hashlib
* sys

## Steps
* Download the Python file
* Run the command: python checkmypass.py <put password here> (seperate password with spaces)
* And Voila! 

