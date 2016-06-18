# 30MillionsPokemons

A (non real) website for purchase Pokemons !

Developped with Twig, Silex and Bootstrap

Project for Polytech Lyon

## Set up
------------

* Download the project and save it in a web repertory (www for WAMP, htdocs for XAMP, ...)  
* Run all sql files (from db repertory) in a phpMyadmin server
* Download <a href="https://getcomposer.org/"> Composer </a>
* Run <code>composer update</code> in the web directory (i.e : where the composer.json file is)


## Good to know
---------------

- A Pokemon is an Article 
- A Category is a "type" of Pokemon (Fire, Water, Poison, ...). A Pokemon can have one or two different types.
- There is a distinction on the application between a simple user (customer) and an administrator (but there is no significal difference yet)
- The layout.html.twig view is the header and the twig template. There is also a backButton.html.twig, that add a "back button" ; and an error.html.twig for display errors to the user. For now, those three pages follow this inheritance : layout -> backButton -> error -> [...]

## Special features
---------------------

- Stock Management (basic)
- User account (with automatic connection)
- Profil image (upload in the repertory) /web/images/users/[idUser].jpeg. 

## Soon
----------

    Add an administration board (with admin account)
    Improve stock management (for administration)
    
## Others
------------

Contact me for any questions !

Please let me know if you have any idea for improvement ;)



