# Email-Template
HTML email template

#Creating the Body and Main Table

- add an overall structure
 - <body> tag setting: 0, 0: avoid any unexpected space.
 - table with a width of 100%
  - acts as a true body tag for our email.
  - cell padding and spacing also set to 0, again to avoid unexpected spacing
- placing a centered table
 - 600 px is convention to be applied to fit most screens
 - golden rule in html email: if an attribute exists in HTML, use that instead of CSS.

-We've also added an inline style property that sets the border-collapse property to collapse. If we don’t do this, newer versions of Outlook will add a small space between our table and our border.
