# Client_ID and CLIENT_SECRET

A How-to guide for obtaining The client id and the client secret for g-up
> **Note**
>
> You will need a google account for login into google cloud
>
{style="note"}

## Setting up google cloud

Guide step by step to configure google cloud for latter getting a CLIENT_SECRET and a CLIENT_ID

1. Go to this [link](https://console.cloud.google.com/projectcreate) and create a new project

2. Now go to [Drive api](https://console.cloud.google.com/apis/library/drive.googleapis.com) and enable it on your project
 ![driveapi.png](driveapi.png)

3. Setting up [OAuth screen](https://console.cloud.google.com/apis/credentials/consent)

<procedure title="OAuth screen config" id="oauth-scr">
    <step>
        <p>Select External</p>
        <img src="external.png" alt="" border-effect="line"/>
    </step>
    <step>
        <p>Select the information as its displayed here, on yourmail put your email</p>
        <img src="oauth1.jpg" alt="" border-effect="line"/>
    </step>
    <step>
       <p>Select this scopes</p>
       <img src="oauth2.png" alt="" border-effect="line"/>
    </step>
    <step>
       <p>Add your gmail to the test users</p>
       <img src="oauth3.png" alt="" border-effect="line"/>
    </step>
    <step>
       <p>Hit <shortcut>GO BACK TO DASHBOARD</shortcut></p>
    </step>
</procedure>

## Getting Client_ID and Client_SECRET keys

> **Warning**
>
> You should [configured google cloud](#setting-up-google-cloud) after getting the keys
>
{style="warning"}

1. Go to [credentials tab](https://console.cloud.google.com/apis/credentials)
2. Hit <shortcut>CREATE CREDENTIALS</shortcut> and select <shortcut>OAUTH client ID</shortcut> 
<procedure title="Create OAuth client ID" id="oauth-client">
    <step>
        <p>Select <shortcut>TVs and Limited Input devices</shortcut></p>
        <img src="TVs.png" alt="" border-effect="line"/>
    </step>
    <step>
        <p>Grab your <shortcut>CLIENT_ID</shortcut> and <shortcut>CLIENT_SECRET</shortcut></p>
        <img src="client_idandsecret.png" alt="" border-effect="line"/>
    </step>
</procedure>