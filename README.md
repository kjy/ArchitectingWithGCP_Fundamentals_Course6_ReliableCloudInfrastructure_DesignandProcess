# ArchitectingWithGCP_Fundamentals_Course6_ReliableCloudInfrastructure_DesignandProcess


Beginning AppServer.  Created a Cloud Deployment Manager template for Appserver.  Created a Deployment Manager template in YAML format. Learned to work with YAML.  Related JSON to YAML and corrected syntax errors in YAML.  Created a prototype template from the documentation by converting the reference to YAML.  Pruned the prototype template to common and required properties.  Used Gcloud commands to interrogate the GCP environment to find the exact values and URIs required to configure the template.  Worked with Deployment Manager to create multiple environments for different organizations and purposes and then de-deployed them after they have served their purpose.   




Package and Deploy.  Overview—Using Deployment Manager templates, including JINJA2 templates, created a virtual machine that loads a python application and dependencies and boots up and configures itself to run a service.  Specifically, deployed a service using a pre-written Python application called “Echo” and using example Deployment Manager templates written in YAML and JINJA2.  Created a deployment package suitable for Deployment Manager using the python package manager, PIP.   Staged package in a Cloud Storage bucket.  Manually tested the application to ensure that it was working properly.  Tested the new service.     




Adding Load Balancing.  Used a pre-written Python application called “Echo” and existing Deployment Manager templates written in JINJA2.  Created a Deployment package suitable for Deployment Manager using the python package manager, PIP.  Staged the package in a Cloud Storage bucket.  Followed best practices and manually tested the application to ensure that it was working properly.  Investigated and gathered information necessary to configure health checks. Used Deployment Manager to Deploy the Echo Load Balancer (LB) service. Tested the new service.  Enabled and verified that health check was functioning.    




Deploy a Full Production Application with Stackdriver (monitoring).  Cloned a public repository of deployment management templates.   Launched a cloud service from a collection of templates. Configured basic black box monitoring of a logbook application. Enabled Stackdriver to configure monitoring, alert notifications, and to set up graphical dashboards, showing CPU usage and received packets with dynamically updating charts on the dashboard. Created an uptime check to recognize a loss of service. Established an alerting policy to trigger incident response procedures.  Used Apache Bench to generate load traffic to test the system and to trigger auto scaling.  Simulated a service outage to test notifications and resiliency features.  Verified receipt of email notification of failure. 
