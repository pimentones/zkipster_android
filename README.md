# zkipster_android

E2E tests demo with Maestro.

How to run the tests:

1. Prepare the android device/emulator
   1.1. Connect and Android device by wireless debug or start an emulator on the local machine
   1.2. Install the zkipster app
   1.3. At the start of every flow make sure the zkipster app is showing the login page

2. Prepare the local machine
   2.1. Clone the github repo to a local machine
   2.2. Install Maestro: https://docs.maestro.dev/getting-started/installing-maestro
   2.3. Using terminal navigate to the flows folder on the repo
   2.4. From terminal run the following command: maestro test [flow_name].yaml
