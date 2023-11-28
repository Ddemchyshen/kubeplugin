# kubeplugin

**kubeplugin** outputs resource consumption for nodes or pods from `kube-system` namespace in the following sequence:
### **Resource Type - Namespace - Resource Name - CPU - MEMORY**

You need to specify the resource type as an argument before running the script. Example `./kubeplugin pod`
