# Lab 0: Validate lab environment

## Scenario

Bellows College is an educational organization with multiple buildings on
campus. Campus visitors are currently recorded in paper journals. The information is not captured consistently, and there are no means to collect and analyze data about the visits across the entire campus.

Campus administration would like to modernize their visitor registration system where access to the buildings is controlled by security personnel and all visits are required to be pre-registered and recorded by their hosts.

Throughout this course, you will build applications and perform automation to enable the Bellows College administration and security personnel to manage and control access to the buildings on campus.

In this Module-lab 0, you will acquire a Power Platform trial and access the Power Platform admin center. In the admin center, you will then create a **Practice** environment that will be used for majority of the lab executions.

## Exercise 1: Setup

### Task 1: Acquire your Microsoft Power Platform trial tenant

1. Navigate to <https://powerapps.microsoft.com> and select **Start free**.

1. Under **Let's get started**, enter the email address <inject key="AzureAdUserEmail"></inject> in the text box and select **Start your free trial**.

1. If you see a prompt that says you have an existing account with Microsoft, select **Sign in**.

1. Enter the password provided below and select **Sign in**.
   * Password: <inject key="AzureAdUserPassword"></inject>

1. If prompted for multifactor authentication, select **Ask Later**.
    
1. Select **Yes** to stay signed in.

### Task 2: Create environment

1. Navigate to <https://admin.powerplatform.microsoft.com> and log in with the credentials provided before if prompted.

1. If you see a Welcome popup, click **Get Started**.

1. Select **Environments** and click **+ New**.

    1. For **Name**, enter **Practice<inject key="DeploymentID" enableCopy="false"/>**

    1. For **Type**, select **Trial** (Do not select the Trial
        (subscription-based) option).

    1. Change the toggle on **Add a Dataverse data store?** to **Yes**.

    1. Leave all other selections as default and click **Next**.
  
    1. Click the **+ Select** button under the **Security group** heading.
   
    1. Select the **None** item under the **Open access** heading and then select **Done**..

    1. Leave the remaining options at their defaults and select **Save**.

1. Your **Practice** environment should now show in the list of Environments.

   >**Note** : Your environment may take a few minutes to provision. Refresh the page if needed.
