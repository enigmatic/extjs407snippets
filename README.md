## ExtJS 4.0.7 snippets for Sublime Text

>#### Xtypes  
Build complext xtype objects with ease, be presented with most relevant config options (or quickly remove them) and their default values (in case you do not even want to bothe removing them).

>#### Event handlers  
Assign event handlers easily without having to remember the arguments returned, or their type since the argument names are psudo-type casted.

### Xtypes
All xtypes are invoked by xtypename apart from fields, which are invoked by their classname, this is to help users of Sublime Text 2 - who can not get variable width of the autocomplete box.

Since I belive that no component should have an id set, but all components should have a name - you are start out by giving your component a name - and then tab your way through properties.  

Your second tab will give you the rest of the config scope for quick removal option in case you want a clean config - and then you tab your way through each config option as a whole while will let you decide how to build your component - editing values comes after you have tabbed through the config options.

Dependent config options are grouped as you tab your way through, and config options that are objects will let you add more as you reach them on your tab tour down the config.  
  
The last tab is the whole object itself for easy copy/paste  
  
### Events

Events are invoked by their name and delivered in their object type configuration - single: false is appended to all events, but can be removed/edited easily (for those who don't wanna set it, just leave it since false is default).

All arguments returned are delivered pseudo type casted, meaning that numbers are prefixed n_, booleans are prefixed b_, strings s_, objects o_, arrays a_, mixed m_ and instances of (mainly Ext components, managers etc..) are prefixed i_

Use and distribute as you wish  
Igor Szyporyn
igor.szyporyn@gmail.com