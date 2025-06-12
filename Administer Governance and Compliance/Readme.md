# Administer Governance and compliance in Azure

Microsoft's documentation on Azure Policy, describes the process of easily navigating to the policy tab. In all honesty, I couldn't see it anywhere so I searched for policy. You can then expand the authoring tab and find assignments as per the MS documentation - https://github.com/MicrosoftLearning/AZ-104-MicrosoftAzureAdministrator/blob/master/Instructions/Demos/02%20-%20Administer%20Governance%20and%20Compliance.md

![image](https://github.com/user-attachments/assets/a022ed2e-36da-42d6-a7cb-0eb72601464a)

Select Assign policy:

![image](https://github.com/user-attachments/assets/af8319c8-239e-40e8-9322-e44864282be7)


The next step is to select policy definition and the assignment name. I've gone with the same choice allowed location, as suggested in MS's documentation.


![image](https://github.com/user-attachments/assets/8025ccdc-718a-44e9-ac0d-d2e12e860c38)


And so the result is shown in the image below, the next part is selecting the parameter and choosing allowed locations. I chose UK South, it's not worth sharing a screen shot of this as it's very straightforward.


![image](https://github.com/user-attachments/assets/57f224d6-5f11-4b75-8f59-f01401b1a2fe)


And the final outcome! A configured Azure policy


![image](https://github.com/user-attachments/assets/42fbfc0c-87d2-4fd6-b016-44061dcd8a6e)


The next step is to create and assign an initiative definition. You need to head over to the authoring tab again and select definitions. Then select initiative definitions. Leave the tab on Create New category and add a policy.


