# Plupload JavaScript Token

This module is an addition to our modified version of the plupload_widget

The plupload_widget module generates 2 cookies, one of which is called UploadToken

UploadToken is a unique identifier generated out of 2 random strings and a timestamp seperated by dashes in the format 'string-timestamp-string'

Since we wanted to not only pass this Token to the plupload_widget for a more specific folder upload, but also use it as a general Drupal Token, this module was created.

If you do not use our modified plupload_widget or do not set a UploadToken cookie anywhere during Drupal node creation this module will not have any effect