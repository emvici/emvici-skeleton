findhit-emvici-skeleton
=======================

skeleton needed by findhit-emvici each time it creates a new project

## If this app is called **emvici** (MVC), why there aren't only the folders for **models**, **views**, and **controllers**?

Models, Views and Controllers on Web environment are excelent for deployment on simple dynamic pages.
Nowadays senior developers just need more than that.

Things like:
* Locales
* Database Migrations
* Server-side and Client-side caching
* Multiple Data Transports on-the-fly
* and so on...

# Structure Explaination

* **configs/** - Here is where all configurations (for core and modules) will rest.
  * configs/**[ENV]**/ - config's sub-folders are meant to define configurations for each environment, if you try to start your app with an environment that isn't present here, it wont start!
* **controllers** - In **MVC**, this is the **C**, Controllers.

