# Configure System Settings #

When you first log in to a new vSphere Integrated Containers instance, you can set the period of validity for login sessions and schedule vulnerability scans.

## Prerequisites

Log in to vSphere Integrated Containers Management Portal with a vSphere administrator or Management Portal administrator account. For information about logging in to vSphere Integrated Containers Management Portal, see [Logging In to the Management Portal](logging_in_mp.md).

## Procedure

1. Select **Administration** > **Configuration**.
3. Under System Settings, modify **Token Expiration (Minutes)** to optionally change the duration of login sessions from the default of 30 minutes.
4. Click **Download** to obtain the root certificate of the vSphere Integrated Containers Registry. 
	
    You must distribute the certificate to the interested parties:

    - vSphere administrators need the certificate so that they can deploy VCHs that connect to the Registry.
    - Developers need the certificate so that they can pull images from the Registry into their Docker client.

5. Under **Vulnerability Scanning**, optionally change the default settings for the scheduled daily vulnerability scanning at 3AM, and click **Save**.

## What to Do Next

Start [Working with Projects](working_with_projects.md) and [Working with Registries](working_with_registries.md).
