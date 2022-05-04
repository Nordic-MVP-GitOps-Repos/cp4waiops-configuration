In pod ``evtmanager-nciserver-0`` to check syntax, do 

``$IMPACT_HOME/bin/nci_policy NCI_0 syntax /<path-to-policy>/policy.ipl``

To push, do

``./nci_policy NCI_0 push impactadmin $IMPACT_ADMIN_PASSWORD /<path-to-policy>/policy.ipl --project Default``
