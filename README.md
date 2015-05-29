This is an ongoing effort to port CORMAS to Pharo ecosystem: http://www.pharo.org/
Current stable version of CORMAS is based on VisualWorks 7.6 and can be found on: http://cormas.cirad.fr/indexeng.htm

:bangbang: Current active development repository is located at **[SmalltalkHub](http://www.smalltalkhub.com/#!/~SergeStinckwich/CORMAS)**

Some documentation (to be cleaned and reorganized) about Cormas is available on the Wiki here: 
https://github.com/cormas/documentation

All issues about the current and ongoing port are here: https://github.com/cormas/cormas/issues

##What is MOOSE
MOOSE is an implementation of pharo
to be completed...

There are several ways to install Cormas in MOOSE

##How to install Cormas in MOOSE 5.1 image using the Pharo laucnher (easiest way)
Downlaod and install the Pharo Launcher developed by INRIA which you can find on smalltalkhub
 http://www.smalltalkhub.com/#!/~Pharo/PharoLauncher

On the main interface of PharoLauncher download and create the template image 
Moose Jenkins / moose-5.1/#1049/moose-5.1.zip
Name the new image as you wish (e.g. Cormas-moose5.1) 
Launch the new image
Left click on the image main interafce (blank sheet) and open the Monticello Browser
Search Cormas package in the .....




##How to install Cormas in MOOSE 5.1 image

Download last version of MOOSE 5.1 here: https://ci.inria.fr/moose/job/moose-5.1/

If you want to install the last stable version:
```Smalltalk
Gofer new
   url: 'http://smalltalkhub.com/mc/SergeStinckwich/CORMAS/main';
   configurationOf: 'Cormas';
   loadStable.
```

If you want to install the development version:
```Smalltalk
Gofer new
   url: 'http://smalltalkhub.com/mc/SergeStinckwich/CORMAS/main';
   configurationOf: 'Cormas';
   loadDevelopment.
```

All packages load into the Cormas-* package names.

## Licence
Cormas is licensed under MIT. See : http://opensource.org/licenses/MIT

## How to contribute to CORMAS

We welcome submissions! A google group exists for this project at http://groups.google.com/group/cormas-dev
