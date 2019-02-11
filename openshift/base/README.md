### Important ###
To support this application on Openshift you need to enable the scc anyuid in your namespaces:

`oc adm policy add-scc-to-user anyuid -z default -n ecommerce-dev`