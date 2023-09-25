# f5xc-intro

Download file to your PC. Script does not need to be run in Galaxy. Using Ubuntu (or something similar), type "./manual-cleanup-v3.sh" (obviously don't type the quotation marks). Then follow the prompts.

Note that this script is designed to delete the objects created for the Intro/Admin course. So it does not delete, for example, Shared Policies created in the WAAP course.
All objects to be deleted assume standardized names, meaning objects named "student..." will be identified and deleted. For example, if a namespace exists called "instructor", the script won't identify or delete it.
As noted in the code, the VOLTERRA_TOKEN (i.e. the API Token generated in F5XC console) must be unexpired and valid.
Also noted in the code, the api_url can be modified to apply this script to other tenants
