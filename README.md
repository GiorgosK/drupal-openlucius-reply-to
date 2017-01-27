# drupal openlucius-reply-to
its a very simple module that modifies the reply_to used by openlucius 

According to this comment https://www.drupal.org/node/2790943#comment-11825823 
$_SERVER['SERVER_NAME'] is used to create the reply to email address 
But if this is not properly set on server level
some servers will deny to send email from non existent mailboxes

# How to install
- download and unzip the module 
- open up openlucius_reply_to/openlucius_reply_to.module and change the reply_to variable to your reply email 
- upload the openlucius_reply_to directory to your modules directory  
- enable it from admin/modules
