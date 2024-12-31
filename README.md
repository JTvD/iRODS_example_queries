# iRODS_querrie_examples
It took me quite some time and searching through forums to figure these calls out. 
Therefore, after some consideration I decided to make them public.
With a bit of luck they might also help others (you) on their way.
When going through the code keep in mind it is not meant to give a complete set of options or write a tutorial.
It is a description of the 'universal' commands I use most often as iRODS user and admin.


## For more background information:
The PRC comes with a bit of documentation: [python irods client (prc)](https://github.com/irods/python-irodsclient), so does [iBridges](https://github.com/iBridges-for-iRODS/iBridges).
The [iBridges tutorials](https://github.com/iBridges-for-iRODS/iBridges/tree/develop/tutorials) are also worth a check. 


However, most information is found in the icomands documentation of the iRODs consortium and not all icommands functions are available in other API's. 
Especially the iADMIN commands: [irods iadmin docs](https://docs.irods.org/4.3.3/icommands/administrator/), which are required to setup the environment and perform maintenance.

To get help in icommand the 'h' flag can be used as shown here:  'iadmin h modrepl'