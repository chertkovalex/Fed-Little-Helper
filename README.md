Fed Little Helper
===
![alt tag](https://github.com/shootermv/Fed-Little-Helper/blob/master/SantaLittleHelper.png)
===
Chrome DevTools Extension that should help Fed quickly create mock server.

Installation
===

 * Open [chrome://extensions](chrome://extensions)
 * Enable 'Developer Mode' checkbox
 * Click 'Load unpacked extensions...'
 * Select the `Fed-Little-Helper` folder

Usage
===

 * While application running, launch the devtools, you should see a new tab called 'Fed Little Helper', keep it open.
 * Do the actions on the site which brings you to the view you need to create/modify the UI functionality.
 * You will see all the requests recorded
 * Modify the responses according to your needs
 * Press "Export" Button To create mock server


Background
===

Most of us familiar with follwoing situation: It is your first day at new place as Front End.  
Teamleader explains you what need to be done.  
It is your first task here and it is looks pretty easy...  
Alas! It cames out that server not ready yet.  
Or - no proper data can be found on your machine (and you dont know how to generate it)  
`So, it looks like you have no choise but sit and wait until someone will do something to make you able to work...`  
Wait a minute! There is a way to do your job without be dependant on "real" server!

You can use `Fed-Little-Helper` for quickly creating server wich serves mock json responses modified for your exact needs.

Features
===

 * Learning curves - records requests-responses for future stand-alone usage
 * Adding and editing requests and responses
 * Using patterns for identifying requests [**future**]
 * 2 modes for request interseption
   * Opaque - whole server mock for stand alone development (regularly using previous communication recordings)
   * Transparent - intercepts selected requests and returns specified responses [**future**]


 