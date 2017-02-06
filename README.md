# sortcomments
Example module to change the sort order of comments in Drupal 8 using function hook_query_TAG_alter. It is possible to configure sort order (newer or older first) per comment field, using the "comment field configuration" in "manage fields and settings" for your content type.

Corresponding issue for Drupal 7:

=> https://www.drupal.org/node/1095656

Drupal 8.2.x database.api.php / Perform alterations to a structured query for a given tag:

=> https://api.drupal.org/api/drupal/core%21lib%21Drupal%21Core%21Database%21database.api.php/function/hook_query_TAG_alter/8.2.x

### Advanced comment field configuration

![configuration](https://cloud.githubusercontent.com/assets/4519686/20665226/0a26cc4c-b55f-11e6-91ed-bfda8f208194.png)

### Preview

##### preview sort flat

![sort_flat](https://cloud.githubusercontent.com/assets/4519686/20665220/04708428-b55f-11e6-8360-9a27e10fce12.jpg)

##### preview sort threaded

![sort_threaded](https://cloud.githubusercontent.com/assets/4519686/20665224/07543dba-b55f-11e6-92b4-1387c1c45708.jpg)

