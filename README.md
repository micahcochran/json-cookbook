# json-cookbook

This is a cookbook of (food) recipes in JSON, which are structured according to [schema.org/Recipe specification](https://schema.org/Recipe).

This cookbook is made using [recipe-crawler](https://github.com/micahcochran/recipe-crawler).  In recipe-crawler, there is a command line program called `taste.py`, which can be used to do some basic querying on JSON cookbooks.

The purpose of this cookbook to test any software that uses recipes.

If you see problems with the data, please open an issue.  There may very well be bugs in the stack that generated this or there may be problems with the website.

`cookbook-100.json` (and it acompanying `license-100.json`) has 100 recipes.

Other editions should be named similarly.  Fixing bugs are recrawling is preferable to

## Licensing

All the recipes are taken from websites that are either licensed Creative Commons or Public Domain.  Those licenses remain.

Websites licensed under Creative Commons licenses with NoDerivatives restrictions were avoided due to it being unclear if compiling it into a cookbook would be considered as "remix, transform, or build upon".  Works by the US Government Data are in general Public Domain ([17 U.S. Code § 105(a)](https://www.law.cornell.edu/uscode/text/17/105)).

Please see the license-\*.md file for details.  Each recipe also has a "license" attribute with a URL that points to the same URL as the license-\*.md.
