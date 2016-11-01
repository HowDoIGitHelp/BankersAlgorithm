MP 1a and 1b
both parts are combined in this tool

a. "enter the number of processes" 
   (enter any whole number)
b. "enter number of processes"
   (enter n integers for n types of resources separated by comma e.g. "45,70,35". 3 processes automatically)
c. "enter process ID"
   (this is the first step of resource request. processes are named 0,1,...,|processes|-1. entering a number n where n<0 or n>=|processes| will terminate the resource allocation and proceed to checking)
d. "enter process requests"
   (enter comma separated whole numbers for each resource type e.g."12,0,34")
   (c and d will repeat until you enter an invalid process ID. entering an invalid process ID (n<0 or n>=) will check if the requests are safe)