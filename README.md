multiple-emails.js
==================

Enter multiple emails in a single input field with jQuery.

This is an improved version of the original work of Pierre https://github.com/pierresh/multiple-emails.js.

## New features are:
- can display emails once the page is loaded
- check integrity of entered email address
- emails are encapsulated in json
- added support for copy and pasting bulk emails in the input field
- works very well with Bootstrap and Semantic UI
- can allow maximum email entered via configuration
- email addresses can be separated by SemiColon(;), Tab, Space and Enter
- Added jQuery Theme delete Icon
- removal of duplicate email addresses in COPY/PASTED text

## Options

	$(selector).multiple_emails({
	   position: 'top', // Display the added emails above the input
	   theme: 'jQuery', // jQuery is the default theme
	   checkDupEmail: true, // Should check for duplicate emails added
	   maxEmailsAllowed: 5, // maximum email addresses allowed (Default:5)
	   placeholder: "user@domain.com" //default placeholder text to be shown
	});
