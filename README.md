# New-Distributed-System-Project-1
Organization Version of this project
-----------------------------------------------------------------------------
This is the readme file of the EZShare Resource Sharing Network Project.
@author Bowen Rao, Zizhe Ruan

Two main classes： EZshareServer.java as server, and Client.java as client.

EZshareServer command line options:
-advertisedhostname <arg>        advertised hostname
-connectionintervallimit <arg>   connection interval limit in seconds
-exchangeinterval <arg>          exchange interval in seconds
-port <arg> 					           server port, an integer
-secret <arg> 					         secret
-debug 							             print debug information

Client command line options:
-channel <arg> 					 channel
-debug 							     print debug information
-description <arg> 			 resource description
-exchange 						   exchange server list with server
-fetch 							     fetch resources from server
-host <arg> 					   server host, a domain name or IP address
-name <arg> 				  	 resource name
-owner <arg> 					   owner
-port <arg> 				     server port, an integer
-publish		 				     publish resource on server
-query 							     query for resources from server
-remove 						     remove resource from server
-secret <arg>				 	   secret
-servers <arg> 					 server list, host1:port1,host2:port2,...
-share 							     share resource on server
-tags <arg> 					   resource tags, tag1,tag2,tag3,...
-uri <arg> 						   resource URI
