# JsonJuggler

# Overview
A tool to quickly visualize and compare mulltiple VxRail installation JSON files.  Works with 7.0.130+.  Will add versions for 7.0.101 and possibly 4.7 as time allows

### Instructions
Place log files in c:\logs\VxRail\JSON (or change the data source in power query) and refresh the query.

## diff sheet
![image](https://user-images.githubusercontent.com/11296072/131400417-7e072c1e-59d9-4e85-b970-dafad09db14e.png)
Quickly compare top level settings between multiple JSON files.

## dashboard sheet
### Cluster level information
![image](https://user-images.githubusercontent.com/11296072/131400601-0ed10f6f-9111-43b7-8fa0-d3a46100a6c2.png)
Top level details about the cluster and when the file was created

### Cluster Details
![image](https://user-images.githubusercontent.com/11296072/131400832-5877d9b9-8166-4df6-979c-0d11e6dea8f5.png)
Cluster details - unset parameters and valyes are hidden

### VLAN Details
![image](https://user-images.githubusercontent.com/11296072/131401168-cfcdfc76-ce2e-432b-878b-7b6875f6640e.png)
Displays whatever values are explicitly set in the JSON file

### Host details
![image](https://user-images.githubusercontent.com/11296072/131401298-69c1c37e-a3c7-485c-857e-4b4b4ea77ccb.png)
Host-specific details
