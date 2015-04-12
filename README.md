Gravity-Forms-Active-Campaign-Add-On
====================================

Integrates Gravity Forms with Active Campaign allowing form submissions to be automatically sent to your Active Campaign account.

Plugin Documentation
====================================

1.	Unzip the activecampaign-gravity-form-addon archive and put the directory "activecampaign-gravity-form-addon" into your "plugins" folder (wp-content/plugins/).
2.	Activate the plug-in
3.	Go to the Forms->Active Campaign Settings page. Save the API KEY and Active Campaign url.
4.	Create a new form
5.	Drag a Text field and set the title as First Name. Now click on Advanced Tab , Check the “Allow field to be populated dynamically” and in Parameter Name field set the value “ar_first_name”
6.	Drag a Text field and set the title as Last Name. Now click on Advanced Tab , Check the “Allow field to be populated dynamically” and in Parameter Name field set the value “ar_last_name”
7.	Drag an Email field and set the title as Email. Now click on Advanced Tab , Check the “Allow field to be populated dynamically” and in Parameter Name field set the value “ar_email”
8.	Drag a hidden field and set the title as List Id. Now click on Advanced Tab, In Default Value field, please enter the List Id of the active campaign where form will be submitted. Check the “Allow field to be populated dynamically” and in Parameter Name field set the value “ar_list_id”
9.	Now add form shortcode in your post or page or sidebar to test it.
10. Incase of Sinlge Name field , click on the Advanced Tab , Check the “Allow field to be populated dynamically” and in Parameter Name field set the value “ar_first_name” for the First Field and set the value "ar_last_name" for the Last Field.


