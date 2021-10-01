# Request for free Microsoft-hosted agents on Azure DevOps

The first time you try to run the personal Azure DevOps pipeline, you might recieve
the following message.

> No hosted parallelism has been purchased or granted. To request a free parallelism
grant, please fill out the following form https://aka.ms/azpipelines-parallelism-request

To request for free Microsoft-hosted agents, please fill the [form](https://aka.ms/azpipelines-parallelism-request).

Please choose the response as **Private** to the below question asked in the form.

> Are you requesting a parallelism increase for Public or Private projects?

You will receive email confirming the approval of the request in 2-3 business days.
Ensure that the project visibility is set to private for the projects created inside
your organization.

![Private project settings](https://raw.githubusercontent.com/Biswajee/Azure-DevOps-Extensions-Workshop/master/demo-images/project-visibility.png)

## FAQ

1. Why is a free parallelism request necessary?

    In [Release 183](https://docs.microsoft.com/en-us/azure/devops/release-notes/2021/sprint-183-update#change-in-process-for-obtaining-free-pipelines-grant-in-public-projects), Microsoft stated the below reasons for adding restrictions on free pipeline use as follows:

    > Over the past few months, the situation has gotten substantially worse, with a high percentage of
    > new public projects in Azure DevOps being used for crypto mining and other activities we classify
    > as abusive. In addition to taking an increasing amount of energy from the team, this puts our hosted
    > agent pools under stress and degrades the experience of all our users – both open-source and paid.

    Hence, a free parallelism request is necessary to execute the pipelines during the workshop.
    In case, you already have a working pipeline in your personal Azure DevOps organization, you
    may skip filling the above request form.
