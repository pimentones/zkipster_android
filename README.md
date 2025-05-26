# zkipster_android

E2E tests demo with Maestro.

How to run the tests:

1. Prepare the android device/emulator
   1. Connect an Android device by wireless debugging or start an emulator on the local machine
   2.  Install the zkipster app
   3.  At the start of every flow, make sure the zkipster app is showing the login page

2. Prepare the local machine
   1. Clone the GitHub repo to a local machine
   2. Install Maestro: https://docs.maestro.dev/getting-started/installing-maestro
   3. Using terminal, navigate to the flows folder on the repo
   4. From the terminal, run the following command: maestro test [flow_name].yaml
