#Infusionsoft API online interface. 

##General outline of this what this application will do:

This application is intended to provide a basic web based interface to an Infusionsoft Application.  This application will be written so that 
it is not neccessarly tied to one application.  It will be written with the intention of a quick troubleshooting test. 

##General outline of how this application will operate:

- [ ] User gets to front page
  - [ ] Application checks if it has an appname and/or API key.

    If the application does not have an appname and/or API key
    - [ ] Application prompts user for details
      - [ ] Application ensures that Appname and API key allow acces.

        If the Appname and API key fail the test
        - [ ] Application removes all info from session and reloads main page. 

    If the application does have appname and/or API key
    - [ ] Application displays various stats of the current application
    - [ ] Application displays menu of potential actions.

