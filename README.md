

![Power Boost for Gravity Forms](assets/banner-1544x500.jpg)

#  power-boost-for-gravity-forms

WordPress plugin. An add-on for Gravity Forms. Enhances Gravity Forms for power users.

Visit this plugin on wordpress.org: [wordpress.org/plugins/power-boost-for-gravity-forms](https://wordpress.org/plugins/power-boost-for-gravity-forms/)

Visit this plugin's home page: [breakfastco.xyz/power-boost-for-gravity-forms](https://breakfastco.xyz/power-boost-for-gravity-forms/)

## FEATURES



### Adds a "Last Entry" column to the forms list.

Indicates which forms are truly active   ![screenshot-1](assets/screenshot-1.png)



### Adds a tab "Replace Forms" to the Import/Export page

Updates existing forms instead of creating duplicates

   ![screenshot-6](assets/screenshot-6.png)



### Adds a "Resend Feeds" button near the Resend Notifications button

![screenshot-4](assets/screenshot-4.png)



### Saves .json file exports of each form when forms are edited

Saved in `wp-content/uploads/gf-json/`. Override this path with the `gravityforms_local_json_save_path` hook.

   ![screenshot-2](assets/screenshot-2.png)



### Adds field IDs near labels when viewing or editing an entry in the dashboard

   ![screenshot-3](assets/screenshot-3.png)



### Adds field IDs near labels when editing forms

Thanks be to Dario Nem for suggesting this snippet from the Gravity Wiz toolbox.

![screenshot-3](assets/screenshot-7.png)



### Adds a "Copy Shortcode" row action link to the forms list

![screenshot-5](assets/screenshot-5.png)



### Enables merge tags in HTML fields

Requires page breaks. Merge tags display user input from previous pages in HTML fields.

Enables merge tags in HTML fields. The merge tag must be on a page after the field. If your field, “What kind of pet do you have?” is on page one of the form, the HTML field containing the merge tag `{What kind of pet do you have?:1}` should be on page two or any page after one.

![screenshot-8](assets/screenshot-8.png)



## Filter Hooks

`gravityforms_local_json_save_path`

   The absolute file path to a directory where the form export .json files are saved. Defaults to `wp-content/uploads/gf-json`
&nbsp;
&nbsp;
`gravityforms_local_json_save_form`

   Allows a forms array containing a single form to be edited just before it is written to the .json file
&nbsp;
&nbsp;
`gravityforms_local_json_minimize`

   Controls whether the form JSON is encoded with the `JSON_PRETTY_PRINT` flag. Defaults to `false`
