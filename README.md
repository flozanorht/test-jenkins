You cannot use all samples here at the same the because they use fixed project and resource names.

On the Jenkinsfile, replace all occurences of

openshift.withProject("test-nobuild2")

with

openshift.withProject()

To run Jenkins and the node.js sample app on the same project

If you know how to create a Jenkins job using its web ui you do not need a build configuration at all.

