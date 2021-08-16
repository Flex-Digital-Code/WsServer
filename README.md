# WsServer and WsClient (for a webhook)

1. This is currently only running as a console app. It will need to be changed/adapted to what is require for ST software. (MVC, BLAZOR, WEB APP etc)

2. Uri serviceUri = new Uri("ws://localhost:5000/send"); this currently only works on localhost (line 21 in Program.cs under WS.client)
   Figure out a way to make localhost visible from an outside source.
   
3. Once Dev environment is visible from an external source. The websocket can be configured. The IP address that links dev environment to local host must be sent to Keonn so they can configure the webhook from their side.
   
