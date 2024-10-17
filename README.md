https://www.youtube.com/watch?v=yacpjV6kWpM&t=387s

 
[ 1 ] From a Windows driver to a fully functionnal driver.  
In this blogpost we'll go through the history of EDR's, how they used to work, how they work now and how we can build a fully functionnal one. Last step is a chall, bypass MyDumbEDR. 
 
https://sensepost.com/blog/2024/sensecon-23-from-windows-drivers-to-an-almost-fully-working-edr/ 
 
 
 
[ 2 ] internal mecanisms of EDR's : 
 
https://www.youtube.com/watch?v=yacpjV6kWpM&t=387s 
 
 
[ 3 ] MyDumbEDR ( written in C ) 
 
https://github.com/sensepost/mydumbedr 
 
⭕️ Join for more: 
 https://t.me/anonymousisontheway
 
# MyDumbEDR 

This repo contains all the necessary files to run the MyDumbEDR and try to bypass.

## To run the project

First you'll have to open the .sln file in Visual Studio 2019 and compile the projects (required stuffs is described in the blogpsot.)

Then you can open the create.bat file and replace absolute links and finally run the bat script which will launch everything :)

For more information about building the project, please take a look at [URL BLOG]

## Rules

The game is simple, bypass the EDR. I wrote code that is voluntary buggued so I strongly encourage you reading the source code of the differents components. This bugued code mimics things that you can encounter while fighting against real EDR's so... Have fun :)

Happy hacking!
