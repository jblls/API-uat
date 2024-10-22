What's On static website.

The client JS reads the JSON uploaded from EZproxy UAT,
using a cronjob that lunches 
/home/nfs/z3541612_sa/libcal/libcal.py 

The python script call the Springshare API to get Events details,
and upload the JSON to Github Pages using PyGithub. 
Need access token generated from Settings > Developer Settings > Access Tokens. 
