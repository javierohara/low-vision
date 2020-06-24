# Living with Linux and Low Vision

## Description

I'm Javier and I have [Low Vision](https://en.wikipedia.org/wiki/Visual_impairment).  Linux is my operating system of choice, so I set it up to help me overcome my disability.

## Desktop Environment

I use XFCE as a desktop environment.  It has desktop zooming integrated and it feels light and responsive.  I find it also easy so set-up.

## Color theme

I prefer a dark theme. Greybrid-dark just does the trick. 

For the window decoration I prefer Greybird-accesibility.  It has nice light borders around windows.

## Desktop zooming

XFCE comes with integrated desktop zoom.  To activate it, you just press Alt and use the mouse wheeel to zoom in or out.

## Locating the mouse pointer

My limited field of vision make me lose the mouse pointer often.  I use a program that makes the pointer very visible and have it binded to a key combo.

The program is locate is locate-pointer and you can get a copy from here.  See top comments for compiling instructions.  I have the executable under /usr/local/bin and bound to super-c. 

## Inverting colors

Sometimes programs don't follow the desktop color theme.  Also sometimes you have to read a very white image.  That's when inverting the colors of the desktop helps out.  

I use xcalib like this:
> `xcalib -invert -alter`

and have it bound to Ctrl-Alt-I

## Browsing the web

I use Firefox as my preferred web browser.  It follows the desktop theme but the contents of the pages are ususally very bright.  

I have installed the [Dark Background, light text](https://addons.mozilla.org/en-US/firefox/addon/dark-background-light-text/) addon which turns very bright sites into dark ones.

## Developing with Eclipse

Eclipse is my IDE of choice (I am a Java developer). It comes with several color themes one of which is High Contrast.

Sadly, the default colors for the High Contrast theme make the IDE unusable.  I have installed a new color theme just because of that and it is really good. 

I use the ["High Contrast-Dark"](http://www.eclipsecolorthemes.org/?view=theme&id=39498) theme.

Here is [How to import a color theme](https://help.eclipse.org/2020-06/index.jsp?topic=%2Forg.eclipse.platform.doc.user%2Ftasks%2Ftimpandexp.htm) in Eclipse.


    Javier O'Hara
    javier.ohara@gmail.com

