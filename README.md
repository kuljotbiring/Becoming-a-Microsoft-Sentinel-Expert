# Becoming-a-Microsoft-Sentinel-Expert <img src="https://skillicons.dev/icons?i=azure" />:cloud:

● Onboarded Azure VM to Log Analytics Workspace
● Created and understand Microsoft Sentinel resource
● Reviewed Data Connectors and enabled Syslog collection

● Used Data Connector to collect Windows VM Security Events
● Created Analytics Rule to detect and create incidents based on Security Events
● Investigated incidents in Microsoft Sentinel

● Used Data Connector rules to collect Windows VM Security Events
● Created Playbook for automated response to Sentinel incidents
● Created Analytics Rule to trigger Playbook for remediation upon active alert detection

● Used Hunting service in Microsoft Sentinel
● Understand Custom Queries and collect results queries
● Understand and create Bookmarks for query results
● Promoted bookmarks to create Incidents in Microsoft Sentinel

Final Assessment

Azure Sentinel Incident Triage Challenge

Your Mission

Your company has had a password breach recently leading to compromised Azure Virtual
Machines, and it's working to improve the security control while also implementing monitoring
solutions to ensure a similar incident does not happen again. The security team discovered the
Azure Sentinel service and wants to leverage it as part of their Security Information Event
Management (SIEM) tool replacement to visualize the cloud resources better. You are tasked to
implement the Sentinel in a resource group and demonstrate how the team can leverage the
incidents dashboard to capture failed login attempts on the Azure VMs using the already
provisioned VM for the lab.

The solution you create must satisfy the following:

● Deploy the resource only in the West US region.
● You must complete the challenge using resources in the provided resource group.
● Create an Azure Sentinel resource leveraging the existing log analytics workspace
provided in the lab
● Enable Data Connector for the Azure VM to collect Security Events using AMA by
creating a Data Collection Rule
● Create a Scheduled Query Analytic Rule that queries the logs to detect the failed login
attempts
● Simulate the password attack by using incorrect username/password combination for the
Azure VM RDP access
● Investigate the incidents and close at least one incident to demonstrate the dashboard
use case.
