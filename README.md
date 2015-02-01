# Intro
Few simple example that show you the power of both indexedDB and WebSQL.
The main.html part is taking two examples of the same code (more or less). 
Both show how to work with WebSQL and indexedDB in order to save data in the client side.

The jqm is a shortcut for jQueryMobile and there you can see the two examples that 
use JQM with indexedDB and WebSQL in order to create a simple web app for todo list.
Classic, no?

# Examples
* The JqueryMobile todo list example is on my project site: http://ido-green.appspot.com/WebSQL-IndexedDB-example/jqm_indexedDB.html 
* I've wrote this post http://greenido.wordpress.com/2012/10/05/how-to-use-indexeddb-simplest-example/ 
that explain the code. I hope to have a more detailed one soon on JQM and both DBs.
* If you have a web app that use WebSQL and you wish to migrate it to leverage indexedDB - This might (also) help you: http://greenido.wordpress.com/2011/11/29/convert-your-websql-to-indexeddb/


(!) Please note that since November 18, 2010, the W3C announced that Web SQL database
is a deprecated specification. This is a recommendation for web developers to no longer
use the technology as effectively the spec will receive no new updates and browser 
vendors aren't encouraged to support this technology. Many major browsers including
Chrome, Safari, Opera and nearly all Webkit based mobile devices support WebSQL, 
however, if you are going to start a new project and/or you wish to have your 
code running with the new version of client side database (that will receive updates
and improvements) you should implement indexedDB as your client side DB.

## Todos
  * Check how it's working in Chrome 42.
  * Check the options to leverage a lib. for multi browsers support.
  
## Be strong
