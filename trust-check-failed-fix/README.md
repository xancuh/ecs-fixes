## trust-check-failed fix

Example:
```Service starting...
Intializing Roblox Web Service
httpGet  failed. Trying again. Error: : Trust check failed, The operation completed successfully.
.  Elapsed time: 0
httpGet  failed. Trying again. Error: : Trust check failed, The operation completed successfully.
.  Elapsed time: 0
httpGet  failed. Trying again. Error: : Trust check failed, The operation completed successfully.
.  Elapsed time: 0
SecurityDataUpdater failed to fetch data from , : Trust check failed, The operation completed successfully.
```
This guide will show you how to fix this.

1. Download HxD [here](https://mh-nexus.de/en/downloads.php?product=HxD20)
2. Drag your RCCService.exe inside or open it from HxD.
3. First of all, check if the RCC is patched with economy-simulator.org or economysimulator.com or just roblox.com. You can do this by doing Ctrl+F and search for roblox.com with all direction and press search all.
4. After that, find which domain is used in the RCC patched and then do Ctrl+R. You must find that domain and put it in the Find box and in the Replace with: box you must put your domain. With ECS, domain length doesn't matter. if you're using another source, then it might.
For example:
```
Find: economy-simulator.org
Replace with: your.domain (Replace with your domain)
```
Make sure the direction is all and do Replace all.
5. Search for ns1 (make sure direction is all) and then click the find button. Highlight the ns1, 2, 3 things and replace them with roblox.com
6. Then save it and run it and there shouldn't be any trust check fails!

NOTE: This may fix item rendering too, so if you cannot render items fast then this might help

Guide by **z9nj** on Discord

