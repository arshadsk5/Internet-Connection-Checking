# Internet-Connection-Checking
How to check the internet connection in ios swift
unzip the folder attached and drag and drop the files into your project.
create a bridge. header file and import as #import "Reachability.h"
Before doing some thing like api calling check the internet connection with the following code as below,
if kNetworkController.checkNetworkStatus() {
 // call your api
 }
