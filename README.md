Mistral Worflow
===============

Mistral is an openstack project that allows to automatize tasks
by executing workflows.


Mistral can be used with via API, CLI or Horizon.
In Horizon, Mistral is found under the dashboard Workflow and show following pannels:
* Workbooks:           obsoleted
* Workflows:           yaml file (in yaql) describing a list of tasks
* Actions:             Openstack API calls or customer-written actions; each task is calling an action
* Workflow Executions: Log of past execution of workflows
* Task Executions:     Log of past execution of tasks
* Action Executions:   Log of past execution of actions
* Cron Triggers:       cron-like job scheduling a workflow


References
==========

* https://docs.openstack.org/mistral/latest/user/wf_lang_v2.html
* https://yaql.readthedocs.io/en/latest/language_reference.html
* https://object-storage-ca-ymq-1.vexxhost.net/swift/v1/6e4619c416ff4bd19e1c087f27a43eea/www-assets-prod/presentation-media/mistral-presentation-austin-2016.pptx
* https://gitlab.cern.ch/cloud-infrastructure/mistral-workflows/
* https://gitlab.cern.ch/cloud-infrastructure/mistral-workflows/raw/master/workflows/instance_snapshot.yaml
* https://translate.google.com/translate?hl=en&sl=zh-CN&u=https://www.fumengji.com/2018/11/21/mistral-workflow-%25E6%25A8%25A1%25E6%259D%25BF%25E4%25BF%25AE%25E6%2594%25B9/&prev=search
* https://github.com/RaymiiOrg/openstack-nova-snapshot/blob/master/create_snapshot.sh

* https://docs.stackstorm.com/mistral.html
* https://github.com/StackStorm/st2/issues/3619 Feature Request - Ability to execute Mistral on-success tasks sequentially #3619 
* https://github.com/StackStorm/st2/issues/3554 Published mistral variables are not available in context immediately #3554 
* https://github.com/openstack/mistral-extra/tree/master/examples/v2/openstack/tenant_statistics
* https://github.com/openstack/mistral-extra/blob/master/examples/v2/openstack/tenant_statistics/tenant_statistics.yaml
* http://www.dougalmatthews.com/2017/Feb/14/mistral-on-success-on-error-and-on-complete/
* https://specs.openstack.org/openstack/mistral-specs/specs/pike/approved/advanced_publishing.html

* https://docs.openstack.org/cinder/latest/admin/blockstorage-volume-backups.html Back up and restore volumes and snapshots
* https://docs.openstack.org/python-openstackclient/rocky/cli/command-objects/server-backup.html
* https://docs.openstack.org/python-openstackclient/rocky/cli/command-objects/backup.html

