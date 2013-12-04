# Site data for badges.rit.edu

This repo contains site data files for the Tahrir deploy
at badges.rit.edu. Included is text for the About page and
the footer.

## Usage

To use these files, simply but them in the root of your project directory and
replace the line in the Tahrir config file with:

    tahrir.sitedocs_dir = %(here)s/fossrit-tahrir-sitedata
