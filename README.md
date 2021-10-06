# robinandsara

Wedding website!

https://self.brockmuellers.com/robinandsara/
https://brockmuellers.github.io/robinandsara

file:///home/sara/repos/robinandsara/docs/index.html

## TODO
* Custom subdomain (robinandsara.brockmuellers.com, wedding.brockmuellers.com, ...?)
* Fun pictures of us
* General content
* How should RSVPs work
* Registry

## Access

Can (maybe) password protect some pages, and possibly switch behavior based on those passcodes?

Ex. have a public page, then include a "Logistics" tab that requires a passcode. Logistics sections are displayed based on passcode (welcome dinner, schedules for photos, ceremony details, etc)

https://stackoverflow.com/questions/27065192/how-do-i-protect-a-directory-within-github-pages

## RSVPs

Some fun ideas from Offbeat Bride for google form RSVPs https://offbeatbride.com/google-docs-wedding-rsvp/

Form 1 (includes +1): https://docs.google.com/forms/d/1E4S2BIoETGy4i2pyZzXX-VuzqjTEnqjJndORG1f1nsE/edit

Form 2 (no +1): https://docs.google.com/forms/d/1-i51E479WwNcnELMJL8heuJTtOltXxcYpQchkCEIyx4/edit

For security/uniqueness:
* Pre-filled forms, each guest can have one with unique URL
* Hidden fields for secure IDs https://stackoverflow.com/questions/20342684/hidden-field-in-a-google-form
* Passwords https://www.instructedtech.com/2016/11/28/3-tips-for-quiz-security-in-google-forms/
* QR code generation https://www.qrcode-tiger.com/how-to-make-a-qr-code-for-a-google-form
* Built in option for captcha to slow down potential spammers

Flow:
* Form has passcode
* Conditional logic - passcode A -> fields for household of invited guests, passcode B -> fields for guests with +1, passcode C -> fields for guests with no +1
* OR everyone has their own passcode (like {firstname}{lastname}) that displays the correct fields

### Making it easy for guests

* Option on invite to go to easy site that redirects to google form (like rsvp.brockmuellers.com) and enter easy passcode
* Option to use QR code on invite - link to pre-filled form that has the email and passcode filled in
* Option to click link in emailed invite - prefilled form with passcode filled in
* On wedding website, direct guests to their paper or email invite
* For older guests, also send a physical, stamped RSVP card

### Making it easy for us

Who knows!!! Some magic with google sheets.

## Design

Inspiration:
* https://www.zola.com/wedding-planning/website/designs
* https://www.theknot.com/gs/wedding-websites/designs

Some other sites on github:
* https://github.com/menzenski/wedding-site
* https://github.com/vittoriom/wedding-site

Basic free HTML templates: https://html5up.net/

## Features that other sites have
* Send invites and updates to all guests
* Possible to see who has opened your invite

## Sections
* Home page
* Our story
* Wedding party
* Events
* Travel
* Things to do
* Photos
* Registry
* FAQs
* RSVP
