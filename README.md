###PANT - Pantheon Administration; Not Terminus

###Purpose:
  Sets up a local development environment for building Drupal sites hosted on Pantheon

###Usage:
  pant operation [site] [env] [profile|access|error] [multisite]

  The default [site] is the current Drupal root and the default [env] is dev.

  [profile] and [multisite] are only necessary for pant install.

###Examples:
  *pant backup*

    Create a backup of the dev environment for the current Drupal site

  *pant code*

    Pull the latest code from the dev environment for the current Drupal site

  *pant db*

    Download the latest database backup from the dev environment for the current Drupal site

  *pant files*

    Download the latest files backup from the dev environment for the current Drupal site

  *pant fix*

    Repair the files and database for the dev environemt of the current Drupal site

  *pant install my-site*

    Install the dev environment for the Pantheon Site Name my-site

  *pant log*

    Display the web server error log from the dev environment of the current Drupal site

  *pant logout*

    Logout of Terminus

  *pant sites*

    List the available sites on Pantheon

  *pant sync*

    Download the latest code, database and files backup from the dev environment for the current Drupal site

  *pant uninstall my-site*

    Uninstall the dev environment for the Pantheon Site Name my-site
