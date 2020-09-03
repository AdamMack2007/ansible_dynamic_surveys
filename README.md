# ansible_dynamic_surveys
This is a quick and dirty example of a dynamic survey playbook for Ansible Tower.

# Notes
When talking to the Tower API you'll need to reference the ID of the object. 

For this example you can see in the second task in the playbook I am updating the survey for Job template 16:

"https://ansibletower.company.com/api/v2/job_templates/16/survey_spec/

This information can be gathered in the Tower UI by navigating to the desired template and looking at the URI.
