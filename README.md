# CS 495: Capstone Computing (Bowfin)

**Project website:** https://cs495-bowfin.github.io/marketing/

**Jira board (account and invitation required):** https://bowfin.atlassian.net/jira/software/projects/DP/boards/1

**Beechnut Kennels Staging Site (WordPress credentials from sponsor required):** https://beechnutkennels.wpcomstaging.com/

## Beechnut Kennels Site

**Beechnut Kennels Facebook (for placeholder photos):** https://www.facebook.com/beechnut.kennels/photos

The `beechnut-kennels-site` directory contains the HTML exports of the WordPress pages created via Elementor. These files can be generated as follows:
1. Open the file within WordPress (not through Elementor) in your web browser.
2. Right-click the page and click `View page source`.
3. Copy the contents of this HTML file into an HTML document.
4. Use the `prettier` extension in VSCode to format the document with `Shift + Alt + F`.
5. Upload the resulting file to the directory with the name of the page.

Note that these exports contain some of the HTML elements used to display the admin features for the site. Since the staging site is currently available to view only with an admin account. A version of the site may be deployed in the near future that does not include these elements, but this is a privacy concern that will be enacted only with express approval from the sponsor.

_**NOTE:**_ Since the work on the product is being completed and back up on the WordPress site, the commits to this repo do not necessarily reflect the quantity of work done on the WordPress site.

## Project Website

The project website is available [here](https://cs495-bowfin.github.io/marketing/). The site is built from the [minimal](https://github.com/orderedlist/minimal) theme created by [orderedlist](https://github.com/orderedlist) on GitHub, and is hosted through GitHub Pages. All files relevant for the project website can be found in the [docs](https://github.com/cs495-bowfin/marketing/tree/main/docs) directory of this repository.
