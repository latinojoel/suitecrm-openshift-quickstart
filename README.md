SuiteCRM on OpenShift
======================

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/latinojoel/suitecrm-openshift-quickstart/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

This git repository helps you get up and running quickly a SuiteCRM installation
on OpenShift. The backend database is MySQL and the database name is the 
same as your application name (using getenv('OPENSHIFT_APP_NAME')).  You can name
your application whatever you want.

Running on OpenShift
----------------------------

Create an account at http://openshift.redhat.com/ and install the client tools (run 'rhc setup' first)

Create a php-5.3 application (you can call your application whatever you want)

    rhc app create suitecrm php-5 mysql-5 --from-code=https://github.com/latinojoel/suitecrm-openshift-quickstart/

That's it, you can now checkout your application at:

    http://suitecrm-$yournamespace.rhcloud.com
    
In the first execution the administrator credentials are admin/admin.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/latinojoel/suitecrm-openshift-quickstart/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

