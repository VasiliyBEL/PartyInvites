# PartyInvites
Form for user invitation.
Web application that allows invited users to respond to an email invitation.
The following requirements have been met:
1) Home page displaying information about the party;
2) Form that can be used to respond to an invitation (repondez s'il vous plait - RSVP);
3) Validation for the RSVP form, which will display a Thank You page;
4) Means of sending RSVP forms by e-mail to the party organizer.

In the context of event invitations, RSVP is a confirmation request from the invited person or people.
RSVP is an acronym for the French phrase Répondez s'il vous plaît, literally meaning "Please answer" or "Please answer".

To send a letter of acceptance or rejection of an invitation, the https://email.netcorecloud.com service can be used to register and use the smtp server.
My code uses the WebMail class to create and process emails, and requires you to enter your data (Views/Home/Thanks.cshtml) to work correctly.
