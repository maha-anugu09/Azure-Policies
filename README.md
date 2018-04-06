# Azure-Policies

In the above attached files there are azure Policies to limit resource types, enforce tags and its values and also to limit locations where the resources can be deployed.
We can pass parameters according to the script. 
The policy rule consists of If and Then blocks. In the If block, you can define one or more conditions that specify when the policy is enforced. You can apply logical operators to these conditions to precisely define the scenario for a policy.
In the Then block, you define the effect that happens when the If conditions are fulfilled. 
For example, you can define to limit the locations where they can be deployed, while limiting the resource types.
By using Azure Policies you can manage the cost and also resources.

Azure Policy
1.	It is a service in Azure which is used for creating, assigning and managing the policy definitions. 
2.	Based on the compliance rules;
a.	Some resources are compliant due to the rules and actions that are enforced by the policy definitions.
b.	Those who are not compliant would have to undergo evaluation.
3.	 The default inbuilt policies that are available are:
a.	It requires SQL server 12.0
b.	The storage account must be deployed with certain SKU sizes.
c.	There are limitations on the resource types based on the organization.
d.	This policy restricts the locations specified in the case of deployment of resources.
e.	There is limitation on the Virtual machine SKUs.
f.	There is a tag and a value that is assigned to a resource.
g.	This policy would enable to specify the type of the resource that the organizations cannot deploy.
4.	All the above policies can be assigned through Azure portal, PowerShell or Azure CLI.
5.	Policy assignment is a policy definition to occur in a specific scope. The scope ranges from a management group to a resource group.
6.	Policy parameters would simplify managing the policies by reducing the number of policy definitions from being created.
7.	The collection of policy definitions which are focused towards achieving a single goal is termed as initiative definition.




