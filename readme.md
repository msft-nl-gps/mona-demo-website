# Basic JavaScript App to demo Mona
This repo is used as a demo for a _very basic_ HTML web application that MONA redirects to.

It implements two pages
 - /purchase 
 - /config
that show how to get some of the query string parametaers passed through by the MONA app. 

This app is intended to be deployed to an Azure static web app

After deploying it you can add/update the MONA configration similar to the below:

 - SaaS offer purchase confirmation URL: `https://<static-webapp-url>.0.azurestaticapps.net/purchase/?subscription={subscription-id}`
 - SaaS offer configuration UR: `https://<static-webapp-url>.0.azurestaticapps.net/config/?subscription={subscription-id}`



This repo has a dev container. This means if you open it inside a [GitHub Codespace](https://github.com/features/codespaces), or using [VS Code with the remote containers extension](https://code.visualstudio.com/docs/remote/containers), it will be opened inside a container with all the dependencies already installed.

Or to explore just press `.` 
