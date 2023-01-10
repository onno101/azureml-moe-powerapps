# Azure Machine Learning Managed Online Endpoints consumed by PowerApps
This repo has contains a few artifacts as addition to the article on network-isolated managed online endpoints consumption by PowerApps. The article can be found [on Medium.com](https://medium.com/@onnovanderhorst/consuming-network-isolated-azure-machine-learning-managed-online-endpoints-from-power-apps-d058de4f3aab)

## Structure of the repo
The repo contains both configuration for  the Power App, Power Automate and data gateway configuration. For creation of managed online endpoints, I am referring to [the Microsoft documentation](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-secure-online-endpoint?tabs=cli%2Cmodel).

## Screenshots of the PowerApps config
Below a few screenshots can be found on the configuration of the app

The first image shows the query that is used to start the run the Power Automate flow through the button

![](/img/ButtonQuery.jpg?raw=true)


The second image shows the query for the output text box

![](/img/OutputQuery.jpg?raw=true)


Another image is an overview of the flow

![](/img/Flow.jpg?raw=true)


Two other screenshots show the settings of the Power Automate 'Connection'

![](/img/Connection1.jpg?raw=true)

![](/img/Connection2.jpg?raw=true)




In case of any questions or concenrs, please raise an issue!

Best regards,
Onno v/d Horst
