# HTML Email Templating

I am learning about HTML email templating and have made a small mock-up email to practice. This is a grid style (created by nesting tables) email template that is responsive to different screen sizes. 
To view the in-browser version of the webiste, [click here](https://emma-belg.github.io/HTMLemail/).

![A full verson of the email display](telenet-email-full.png)

![When the email begins to wrap](telenet-email-wrap-1.png)


### Some things I have learnt
Firstly, I have only just begun learning this so I may be missing something important or there is also the posibility that I have learnt something incorrectly from an online resource. I look forward to doing more research and learning further.
  - To keep the majority of 'email clients' happy it is important to use xhtml or HTML4 as these languages are compatible with most email clients. 
  - HTML emails use a nesting table structure to create a type of grid.
  - HTML emails use in-line CSS styling.  
  - It is recommended to not have any spaces in the inline styling for html email
  
### Some notes about styling
  - For outlook compatibility:
      - it is useful to have a capital M for the margin property.
      - it is better to use padding-top, padding-bottom etc instead of just "padding"
  - Some email clients will change the border spacing so it is useful to add "border-spacing: 0;" where you do not wish anything to be changed
