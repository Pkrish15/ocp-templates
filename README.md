# ocp-templates
The Main purpose of the Repository is create objects in Openshift using templates.

# spark-template.yaml

1) This template will create the Master and 3 Worker Nodes in Openshift Environment.
2) Usage: oc login -u prakrish-redhat.com -p xxxxxx https://master.dev39.openshift.opentlc.com/
3) oc new-app https://raw.githubusercontent.com/Pkrish15/ocp-templates/master/spark-template.yaml
4) oc expose svc/spark-master-webui
5) You can view your spark nodes http://spark-master-webui-tk.apps.dev39.openshift.opentlc.com/ replace "tk" with your own project namespace.
  
# Kafka-Template.yaml

1) This template will create a Kafka cluster on your openshift environment.
2) Usage: oc login -u prakrish-redhat.com -p <XXXyourpasswordXXX> https://master.dev39.openshift.opentlc.com/
3) oc create -f https://raw.githubusercontent.com/Pkrish15/ocp-templates/master/resources.yaml
4) oc new-app apache-kafka
  
