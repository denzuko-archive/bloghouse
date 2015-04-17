Project Repostory space:

The static content should be put in the $TRAC\_ENV/htdocs folder, and is accessed by URLs like 

<project\_URL>

/chrome/site/.... or under the vhost webroot folder (ie /var/www/sites/repos/) don't forget to set up your yum and tsunami/flatfile repositories in there as well.

Example: given a $TRAC\_ENV/htdocs/software-0.1.tar.gz file, the corresponding relative URL would be /

<project\_name>

/chrome/site/software-0.1.tar.gz, which in turn can be written using the relative link syntax in the Wiki: [/

<project\_name>

/chrome/site/software-0.1.tar.gz]