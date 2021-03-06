# Tannhäuser Quick Reference
This is a Tannhäuser Quick Reference providing information about the equipment, troops and their different packs.

A live version can be found on[tannhauser.bubblesort.me](http://tannhauser.bubblesort.me).

# Development
With the development environment you can easily edit or add Items and Characters.

To set up this grav skeleton do the following:

1. Install grav and its dependencies
2. From the grav directory a new sandbox site with:

        bin/grav sandbox ~/public_html/tannhauser

3. Clone this repository to the newly generated sandbox

        https://github.com/stylesuxx/tannhauser ~/public_html/tannhauser/user

4. Start a local server on **port 1111** from the sandbox:

        cd ~/public_html/tannhauser/
        php -S localhost:1111

You should now see the page when browsing to [localhost:1111](http://localhost:1111)

## Optional
If you want to add new pages via admin interface you need to install it and add a user:

    bin/gpm install admin
    bin/grav newuser

Now browse to [localhost:1111/admin](http://localhost:1111/admin) and log in with your newly created credentials.