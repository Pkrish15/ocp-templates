# ocp-templates
The Main purpose of the Repository is create objects in Openshift using templates.

# spark-template.yaml

1) This template will create the Master and 3 Worker Nodes in Openshift Environment.
2) Usage: oc login -u prakrish-redhat.com -p xxxxxx https://master.dev39.openshift.opentlc.com/
3) oc new-app https://raw.githubusercontent.com/Pkrish15/ocp-templates/master/spark-template.yaml
4) oc expose svc/spark-master-webui
5) You can view your spark nodes http://spark-master-webui-<your project namespace>.apps.dev39.openshift.opentlc.com/
  
