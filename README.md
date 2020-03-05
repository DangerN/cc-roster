# :cloud: CloudChan :cloud:

This is a directory of the micro-services that support CloudChan.

## Roster
### [Alpha](https://github.com/DangerN/cc-alpha)
Library for handling models.

### [Bravo](https://github.com/DangerN/cc-bravo)
Serves the CloudChan interface.

### [Charlie](https://github.com/DangerN/cc-charlie)
Serves read only API endpoints and listens for updates from Delta.

### [Delta](https://github.com/DangerN/cc-delta)
Provides API endpoints for the creation of new posts and threads. Updates Charlie on changes to site image. Verifies user auth with Foxtrot

### [Echo](https://github.com/DangerN/cc-echo)
Stores and serves media files.

### [Foxtrot](https://github.com/DangerN/cc-foxtrot)
Handles user account concerns. Responsible for user authentication as well as serving user data.
