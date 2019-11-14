# Node - Create Conference Tutorial

This project serves as a guide to help you build an application with FreeClimb. View this tutorial on [FreeClimb.com](https://docs.freeclimb.com/docs/create-a-conference-and-add-participants-1#section-javascript). Specifically, the project will:

- Accept incoming calls
- Receive digits from the caller
- Create conferences
- Add participants to conferences

This application will receive calls and have users enter the conference code of the conference they wish to join. It will then either create the conference or add the caller to an already existant conference. 

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb).

## Setting up the Tutorial

1. Install the node packages necessary using command:

   ```bash
   $ yarn install
   ```

2. Configure environment variables (this tutorial uses the [dotenv package](https://www.npmjs.com/package/dotenv)).

   | ENV VARIABLE            | DESCRIPTION                                                                                                                                                                             |
   | ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
   | ACCOUNT_ID              | Account ID which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard                                                         |
   | AUTH_TOKEN              | Authentication Token which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard                                               |
   | HOST | The host url where your application is hosted (e.g. yourHostedApp.com) |

## Runnning the Tutorial

1. Run the application using command:

   ```bash
   $ node createConference.js
   ```

