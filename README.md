# bash_read_env
Read environment variable in bash scripting.


# This function allows you to get the value of an env variable
## read_var()

# First parameter is the ENV variable you want to read.
# Second parameter is if you want to specify the .env file to read. (Default is .env)

# Usage
Store to a variable like so:
* my_var=$(read_var VAR)
* my_var=$(read_var VAR .env.dev)