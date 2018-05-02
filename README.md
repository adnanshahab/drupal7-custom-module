# drupal7-custom-module
CONTENTS OF THIS FILE
---------------------
   
 * Introduction
 * Requirements
 * Installation
 * Configuration
 * Troubleshooting

INTRODUCTION
------------
This module(Block Display Article) will list five records of node-type 'article' with 'Invention' in title in a tabular format sorted by last updated/changed date.
The default settings of module are shown below:
•	No. of Records: <5>
•	Type of node to search: <Article>
•	Search Text in Node Title: <Invention>

   
REQUIREMENTS
------------
•	The custom module has been developed and tested for Drupal7.x version.
•	It does not require any extra module and it uses only core drupal modules.
•	User having role to <administer site configuration> can configure the default settings and parameters of this custom module.
•	However, once configured, it will display the required table for other users.


INSTALLATION
------------
 
 * Install as you would normally install a contributed Drupal module. Visit:
   https://drupal.org/documentation/install/modules-themes/modules-7
   for further information.


CONFIGURATION
-------------
 
To Configure the settings for the module, click on the configure link within admin/module page.
Go to admin>>config>>block_display_article
Set the following parameters to change the default settings:
1. Search Text within Title field (Enter non-blank string)
2. No. of Record to fetch (Enter any positive number)
3. Node Type 

TROUBLESHOOTING
---------------

 * If the module does not display the , check the following:

   - Does your Drupal site contain some nodes with required text as title?
   - Have you configured the number of record settings within the configuration?
   - Have you checked the block appearance settings in admin>>structure>>blocks?
