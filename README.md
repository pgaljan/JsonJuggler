# JsonJuggler

# Overview
A tool to quickly visualize and compare mulltiple VxRail installation JSON files.  Works with 7.x.  Will explore 4.7 as time allows.

### Instructions

Place log files in c:\logs\VxRail\JSON (or change the data source in power query) and refresh the query.

## Search support 
![image](https://user-images.githubusercontent.com/11296072/131570821-b4fca8dc-43f9-4eb7-bcb8-6745ce5def21.png)
Notes:  
- search string operates against the entire JSON file
- Drop downs on the respective worksheets are linked to the search string filter 

## diff sheet
![image](https://user-images.githubusercontent.com/11296072/131400417-7e072c1e-59d9-4e85-b970-dafad09db14e.png)

Quickly compare top level settings between multiple JSON files.

## dashboard sheet
### Cluster level information
![image](https://user-images.githubusercontent.com/11296072/131400601-0ed10f6f-9111-43b7-8fa0-d3a46100a6c2.png)
![image](https://user-images.githubusercontent.com/11296072/131400832-5877d9b9-8166-4df6-979c-0d11e6dea8f5.png)

Top level details about the cluster and when the file was created

### Summary boxes
![image](https://user-images.githubusercontent.com/11296072/131570984-45c40bfc-adb2-4194-b63a-116112bd387b.png)
Notes:
- Text in boxes are CSV, and can be copied out and into tabular format (on windows, at least)

### VLAN Details
![image](https://user-images.githubusercontent.com/11296072/131401168-cfcdfc76-ce2e-432b-878b-7b6875f6640e.png)

Displays whatever values are explicitly set in the JSON file

### Host details
![image](https://user-images.githubusercontent.com/11296072/131402589-07d5d21f-7df2-4ac7-a1a3-e61ffbae0fb0.png)


Host-specific details
