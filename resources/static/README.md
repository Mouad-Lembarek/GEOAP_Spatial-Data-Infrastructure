Public documents for your SDI
=============================

This repository contains a collection of public files which are, if not required, very useful to host at the root of your SDI domain:
 * the ```errors``` folder has a file which is displayed in case a webapp is temporarily available (HTTP 50x).
 * ```robots.txt``` prevents web bots to harvest your SDI in an undesirable fashion.
 * ```favicon.ico``` is your site favicon. It should probably be customized.
 * ```crossdomain.xml``` is to allow [remote flash applications](https://developers.arcgis.com/flex/guide/using-crossdomain-xml.htm) to use your web services.

Please refer to the [documentation on apache configuration](https://github.com/georchestra/georchestra/blob/master/doc/setup/apache.md#directory-structure) for a detailed guide.
