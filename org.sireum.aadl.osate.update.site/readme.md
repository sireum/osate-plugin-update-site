# Github hosted Sireum OSATE Plugin Update Site

## Installation
1. Install and launch [OSATE](http://osate.org/download-and-install.html)
2. Navigate to ``Help > Install New Software ...``
3. Click ``Add...`` and in the ``Location:`` field paste the following URL

    https://raw.githubusercontent.com/sireum/osate-plugin-update-site/master/org.sireum.aadl.osate.update.site/site.xml
  
4. Check the box for ``Sireum OSATE Plugin`` and click ``Finish``

## For Developers
Run [merge.sh](merge.sh) after building the update site (under eclipse ``Run > External Tools > Merge Sireum jar``).

Note that features are not categorized when the update site is used as a local site so you will
need to uncheck ``Group items by category``
