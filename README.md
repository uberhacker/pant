###PANT - Pantheon Administration; Not Terminus

###Purpose:
  Sets up a local development environment for building Drupal sites hosted on Pantheon

###Installation:

  *Currently, this script will only work in Debian/Ubuntu and derivative Linux distros*

```
  $ git clone https://github.com/uberhacker/pant.git
  $ cd pant
  $ chmod +x pant
  $ sudo cp pant /usr/local/bin
```

###Usage:

```
  $ pant operation [site] [env] [profile|access|error] [multisite]
```

  *The default [site] is the current Drupal root and the default [env] is dev.*

  *[profile] and [multisite] are only necessary for pant install.*

  *[access|error] are only necessary for pant log.*

###Examples:
  *pant aliases*

    Print a summary of all Pantheon aliases

  *pant backup*

    Create a backup of the dev environment for the current Drupal site

  *pant code*

    Pull the latest code from the dev environment for the current Drupal site

  *pant config*

    Manage the local system configuration

  *pant db*

    Download the latest database backup from the dev environment for the current Drupal site

  *pant domain*

    Print the Pantheon domain for the dev environment of the current Drupal site

  *pant files*

    Download the latest files backup from the dev environment for the current Drupal site

  *pant fix*

    Repair the files and database for the dev environment of the current Drupal site

  *pant info*

    Retrieve information about the current Drupal site

  *pant install my-site*

    Install the dev environment for the Pantheon Site Name my-site

  *pant log*

    Display the web server error log from the dev environment of the current Drupal site

  *pant logout*

    Logout of Terminus

  *pant sftp*

    Login on Pantheon via sftp in the dev environment of the current Drupal site

  *pant sites*

    List the available sites on Pantheon

  *pant stats*

    List the local system statistics

  *pant sync*

    Download the latest code, database and files backup from the dev environment for the current Drupal site

  *pant uninstall my-site*

    Uninstall the dev environment for the Pantheon Site Name my-site

  *pant update*

    Update composer and associated packages
