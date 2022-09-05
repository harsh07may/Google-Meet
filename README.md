# Google-Meet-API

Unofficial Google Meet API that Creates and Lists Events using Google Calendar API thereby allowing users to create Google Meet Links.

### Prerequisites
- To run the application make sure you have [NodeJS](https://nodejs.org/en/) installed.
- A Google Cloud Platform project with the API enabled. To create a project and enable an API, refer to [Create a project and enable the API](https://developers.google.com/workspace/guides/create-project)
  - **Note:** For this quickstart, you are enabling the "Google Calendar API".
  - **Note:** Add http://localhost:**port** and http://localhost:**port**/oauthcallback in Javascript Origin URI and Redirect URI respectively.(Replace port with suitable no.)
- Authorization credentials for a desktop application. To learn how to create credentials for a desktop application, refer to [Create credentials](https://developers.google.com/workspace/guides/create-credentials)
- A Google account with Google Calendar enabled.

### Commands:
```
git clone https://github.com/harsh07may/Google-Meet.git
npm install
```
**Note:** Download the OAuth JSON File and place it in the same folder renamed as `credentials.json`.
