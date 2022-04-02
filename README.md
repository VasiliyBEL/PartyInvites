# PartyInvites
Form for user invitation.
Web application that allows invited users to respond to an email invitation.
The following requirements have been met:
1) Home page displaying information about the party;
2) Form that can be used to respond to an invitation (repondez s'il vous plait - RSVP);
3) Validation for the RSVP form, which will display a Thank You page;
4) Means of sending RSVP forms by e-mail to the party organizer.

В контексте приглашений на мероприятия, RSVP — это запрос подтверждения от приглашённого человека или людей. 
RSVP — это акроним французской фразы Répondez s’il vous plaît, означающей буквально «Будьте добры ответить» или «Пожалуйста, ответьте». 

Для отправления письма о принятии или отклонения приглашения может использоваться сервис https://email.netcorecloud.com для регистрации и использования smtp-сервера.
В моем коде для создания и обработки электронных сообщений используется класс WebMail, для корректной работы требуется ввести свои данные (Views/Home/Thanks.cshtml).
