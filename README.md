# Cachet [![OpenShift](https://raw.githubusercontent.com/pcon/sticky-notes-quickstart/master/public/openshiftDeploy.png)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges%5B%5D=http://cartreflect-claytondev.rhcloud.com/github/StartledPhoenix/openshift-cachet-hhvm&cartridges%5B%5D=mysql-5.5&name=cachethq&initial_git_url=https://github.com/StartledPhoenix/openshift-cachet-new.git&initial_git_branch=master)

## IMPORTANT

Please choose which branch you want to install wisely.
By default, to match the Cachet git repository, the L5 branch is selected.

## Installation Errors

Most of the installation errors are caused by errors in Cachet itself.

As mentioned on [cachethq/Cachet](https://github.com/cachethq/Cachet), Cachet is still under development and things may break.

## Auto Update

Noting the above, this particular Cachet installer has an autoupdate script in $OPENSHIFT_REPO_DIR/.openshift/cron/daily/autoupdate

Feel free to remove if you wish.
