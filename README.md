# TxilioText
Python app for using Twilio to send personalized, mass SMS messages to subscribers

*Infant stages of development*

Requirements:
1. Send a *personalized* text blast to a Google Sheets list of Names and Cell numbers
2. Reply to individual subscribers
3. View individual subscriber conversation
4. Test blasts can be personalized using {FNAME} or another identifying string
5. Send test test message to a single SMS number without losing draft message
6. Send links to subscribers
7. Get notified when subscriber replies, without using a text message (maybe use email?)
8. Subscriber reply notification includes link to app to check messages
9. Simple, clean interface
10. Mobile-friendly: can send text blasts from cell phone and reply from cell phone (without cluttering up default messaging app on phone)
11. Subscribers can sign up via web page that writes directly to the Google Sheet - this web page will have a layer of protection that guards against bot blasts
12. Handles voice calls by playing a pre-recorded message (does not forward calls to cellular device).
13. Records voicemail and saves audio recording to online repository.
14. Sends email notification of voicemail received.
