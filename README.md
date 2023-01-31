# demo

<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/nkMr2fl.png" alt="Project logo"></a>
</p>

<h1 align="center">OrgType CLI Tool</h1>

Easily manage your organization types with just a few commands on your terminal! Orgtype CLI Tool is the command line tool for listing, creating and updating orgtypes for various environments of Spyderbat!

### How to use it?- 

./main list -t="" -b=""

flags, can change the env, token values etc


## ./main -help

### Usage of list:
  -b string
  
        base URL for the API request (default "https://api.kangaroobat.net")
  -p string
  
         *not required*,use to make the api request, do -p token value (default "https://api.kangaroobat.net/api/v1/internal/org_type/")
  -t string
  
        description: token value

### Usage of create:

  -b string
  
        base URL for the API create request (default "https://api.kangaroobat.net")
  -p string
  
        *not required*, creates the orgtype at the desied path name,  (default "https://api.kangaroobat.net/api/v1/internal/org_type/defaultuid")
  -t string
  
        description: token value
  -uid string
  
        Org UID, required (default "defaultuid")

### Usage of update:
  -b string
  
        base URL for the API update request (default "https://api.kangaroobat.net")
  -p string
  
        *not required*,use to make the api request, not required, do -otp token value (default "https://api.kangaroobat.net/api/v1/internal/org_type/defaultuid")
  -t string
  
        description: token value
  -uid string
  
        Org UID, required (default "defaultuid")
