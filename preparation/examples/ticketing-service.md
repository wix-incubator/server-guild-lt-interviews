# Problem: Ticketing Service

## Use-case
Enable purchasing tickets on Wix sites.

## Task
Design service that allows reservation and purchase of tickets in user sites.
- User may reserve tickets for 10 mins.
- User may purchase multiple tickets at once.
- There is a limited number of tickets available.
- Ticket is sent to the user as PDF attachment.

You may assume there is a remote payments provider service. Typical flow:
- User gets redirected to the payments provider.
- User does something over the provider.
- User gets redirected back to your service with details in the query (success, failure, ...).

You may assume there is a remote mailing service.

## Some numbers present in the system currently
- 100M+ sites.
- There are sites with 1000+ articles.
- There are sites with 1.5M+ page loads per day.
