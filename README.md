Power-Django-Openshift
======================

*tool to bootstrapping a Django1.7 project on [Openshift](www.openshift.com).*

##useage

    $./openshiftdeploy.sh <Project-name>

###This Script 

    1. will create a new project on openshift.
    2. add mysql 5.5 cartridge in that project.
    3. create a new Django project in that directory.
    4. start a new app in Django project.
    5. make proper settings in wsgi.py and settings.py for Openshift.
    6. create the action_hooks to deploy project on openshift.
    7. push the code to the repository on openshift.

