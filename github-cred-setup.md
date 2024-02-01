# How to set up your GitHub Credential to import a ServiceNow app from a Git Repo

## Exercise 1 - Generate the token

1. Log into GitHub.
1. In the top-right, click your avatar image. 

    ![](images/2024-02-01-09-29-26.png)

1. Click Settings.

    ![](images/2024-02-01-09-31-02.png)

1. Click Developer Settings. (*It's at the bottom of the left hand menu.*)

    ![](images/2024-02-01-09-31-53.png)

1. Click Personal access tokens >> Tokens (classic)

    ![](images/2024-02-01-09-33-11.png)

    ![](images/2024-02-01-09-33-48.png)

1. Click Generate new token >> Generate new token (classic)

    ![](images/2024-02-01-09-34-16.png)

1. Give a descriptive Note for what this token is for.

    ![](images/2024-02-01-09-35-48.png)

1. Set an Expiration that you are comfortable with. (*Or be lazy and set to No expiration* 😎 )

    ![](images/2024-02-01-09-37-23.png)

1. Check at least the repo options.

    ![](images/2024-02-01-09-38-14.png)

1. Click Generate Token at bottom of page. 

    ![](images/2024-02-01-09-38-54.png)

1. Copy the personal access token. Save it in the same secure location that you store passwords such as a post-it note or a unencrypted text file on your desktop. Be sure to name it something like "GitHub ServiceNow Token". 

    ![](images/2024-02-01-09-40-22.png)


## Exercise 2 - Put the token in ServiceNow
1. Log into your ServiceNow instance. 
1. Go to **Connections & Credentials** >> **Credentials**
1. Click **New**
1. Click **Basic Auth Credentials**
    - **Name:** A cool display name (Ex. Dale@GitHub)
    - **User name:** *The email address you use to log into GitHub with.*
    - **Password:** *The token that you generated in Exercise 1.*
1. Click **Submit**
