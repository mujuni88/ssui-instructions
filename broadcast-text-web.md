# Broadcast Messaging(web)

## What is a Broadcast Message?
Broadcast messages allow you as a user to send messages to multiple recipients, beyond that it is basically a normal text message as far as the contact is concerned. 

The use case is if you wanted to send the same message to say: an algebra class, students going on a field trip, or a few students' contacts - you can. 

## What a Broadcast Message is not
Because broadcast messages rely on the same infrastructure as our standard text messages, they can be slowed down if many messages are being sent at once. We have thousands of users who at any point could be sending messages and those messages added to the queue could mean "long" delays for large numbers of recipients.

> “Bring your permission slips to homeroom tomorrow”

Is a good example

> “The school was just hit by a meteor pick your children up immediately”

is not

For this reason we restrict the ability to send large broadcasts. Our average district has 60,000 contacts which could take the better part of a day to deliver. 

## Testing instructions


1. First click the new "Broadcast Item" in the nav bar at the bottom.
![Local Image](/images/broadcast/click-new-button.png)
2. The Broadcast sidebar should open.
![Local Image](/images/broadcast/sidebar-should-open.png)
3. You may or may not see items listed here in the outbox, we will worry about that later
4. Click on the New Broadcast button:
![Local Image](/images/broadcast/click-the-fab.png)
5. A new broadcast window should pop up. You’ll notice the send button is disabled, this is because you need recipients and a message before a message can be sent.
![Local Image](/images/broadcast/create-broadcast-modal-opens.png)
6. As you begin typing in the search field, recipients that match your search appear, it will search for whatever is selected, groups if groups is selected, courses if courses is selected, and contacts if contacts is selected.
![Local Image](/images/broadcast/search-for-recipient.png)
7. Now compose a message. Once you have selected some recipients and typed a message, the send button will turn a darker blue, and you can click it to send.
![Local Image](/images/broadcast/type-a-body.png)
8. Upon sending, the boxes will clear and a success message will be displayed
![Local Image](/images/broadcast/send-confirmation.png)
9. The message should now appear in the sidebar. The name will be the name of whatever the recipient type was, or a number of them if multiple were selected.
![Local Image](/images/broadcast/outbox-items.png)
10. Now upon clicking an entry in the broadcast sidebar (or outbox) the sidebar will give you details in a similar manner to how the messages sidebar work. This details pane shows you what the message was, who it was sent to by group, course, and contact and who (contacts) ultimately received the message. This may not yet be populated as it can take a moment for the messages to actually be sent by the server.
![Local Image](/images/broadcast/message-detail.png)
11. Navigating to the traditional places to see messages, either the messages sidebar or the engagement tab on the student, you should now see an orange chat bubble and the text _this message was sent to multiple recipients_ under the message designating that this particular message was a broadcast.
![Local Image](/images/broadcast/broadcast-chat-bubble-engagement.png)
![Local Image](/images/broadcast/broadcast-chat-bubble-sidebar.png)
