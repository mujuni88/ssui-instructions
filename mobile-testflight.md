# SchoolStatus TestFlight

**Schoolstatus Mobile** has seen some redesign lately. Feedback on design is *always* wanted. Here's some of what you can expect to see

	
![enter image description here](https://lh3.googleusercontent.com/CUDGswBcGdNvMzKJGw1WQkSaoO1y6iKpVtrGxiqeLdVpAzAKKAiUOf6z1_dGkF0xEv7vYVtvHwE) ![enter image description here](https://lh3.googleusercontent.com/ZQcGV218BQfWjmZbtxQNfgzeiM8aP9EN2F93Wj22bxRE6weZl4o71Ihm8yvIhFc41oyxg8VtUqo)   ![enter image description here](https://lh3.googleusercontent.com/HqTTxqI2bBG2DtCzl52KQxkpf1rFFAxWaig9a7GoCn1Os_ULBaNUpEfipXz4fstlm9hn9V_hZQM) ![enter image description here](https://lh3.googleusercontent.com/C8t0xR6GyXxh4VCCGrUVMwF4xPSengsQN9YlgZdhG-kRo95ZP4OzKYQBsEvC14byLVV4adugf-E)

	

## BROADCAST
 
 We start here, at our Broadcast outbox (which depending on your title, may show other users' broadcasts in addition to yours.)
 
![enter image description here](https://lh3.googleusercontent.com/O-DO58OgNfEa4IZZJgiJZ6f35g18bpUkJd_mV_BZ6bhaHfgd3t53Am5Woq_l7X5YzYSmYhsDfE8)



Let's tap the + icon to create a new broadcast.

Let's select 'Contacts' here (or Courses and Groups), and then search/select the multiple contacts we want to send a broadcast to. You can, of course, deselect any recipient if needed, just by tapping on the appropriate search item or the recipient item in the horizontal list above the search bar.

![enter image description here](https://lh3.googleusercontent.com/87YsSGk3Bfo5pzcCN2uOn6-WVn_DQ0B7ntCWzjWoUaDqedS41txpnYU9h7T4PxNmdKdfNzPVT0k)


**You won't be able to proceed without having at least one recipient selected and without having less than 150 recipients.**

Once you hit 'Create Message', you should land here. Compose your message and tap the send button at the bottom right.

![enter image description here](https://lh3.googleusercontent.com/O3QzeX1SpuIjuV9kJ6zOItvvFsfbQuwBLGLa0JWo-1QVdzYB6RcEDdKJQZeAQQCrY_Dzn1fKKoU)


There you go! Unless you're my boss, it probably worked out nicely for you, and you should see a success message.

![enter image description here](https://lh3.googleusercontent.com/eDpVvNMMJSAqC7B1QBjTTIKDpHFmr_WTDQAtZwqAksvtZpENHyfEgKB-0MmjiNKUcXs4zsBlJqE)


Now let's go back to our Broadcast Outbox screen.

![enter image description here](https://lh3.googleusercontent.com/p3t8oMZv-eXpWwB-lC4uHEaJhGWvaSsC6Hpn_J69kx27IPsewgFu6fOhDq0J7rLSTFK28R-nMRI)

Let's tap on the broadcast we just sent to view the details.

![enter image description here](https://lh3.googleusercontent.com/716OgMXWgCne6BUVboVYxBO6J4hvnPkEihwzA34nyyOZw1oFVng0BobUsKLLFBoX2Hs8xA8zx4M)


And that's broadcast messaging in a nutshell.




## Incoming Calling

In order to receive incoming, you and the contact in question must have an established call log. So let's first find a contact (it can be yourself, although you probably will find calling yourself weird and not easy to test)

![enter image description here](https://lh3.googleusercontent.com/QbByJMHCLxjvF396MSYwdvO0Vc6yzpWF0SfxzGHSgC55rEZpMRGSh5u2ZSWC0cIURRydzPA4TDQ)

Select the contact, and call him/her from the next screen.

Now that there is an established call log between the two, the person that was called (you, if you called yourself as a contact or someone else) can call the number back and then press '2' within the automated menu. This will place a call directly with the user that had called them.

![enter image description here](https://lh3.googleusercontent.com/ul5TwWX_ZK_I1sffOPOkox5gTUj4_cG1ouoxk4A-voSCXa5MJoYzlPpH568xqIvfbLSaCV1MAGA)

You'll be able to accept the call and start talking to the person (unless you're trying to call yourself, in which case, you'll at least be able to accept the call)

## Parent Verification

When a potential user is created through our web frontend, in the Parent Access Management module, that potential user receives a text and email with two codes: phone and email verification codes.

![enter image description here](https://lh3.googleusercontent.com/vKvcaCN8X8SD5pukECKwd2yhNjxAgTojAicTqzRHzyFFnNLsRVDeHsmS4429zwbB3hFZrrR4Rnw)

Tap the link in the text message, and then you will be prompted to open the app. Go ahead and accept that.

You should see the following screen
![enter image description here](https://lh3.googleusercontent.com/UF28Qe3aH3NmsDk6hU0Xm0L-_qr1pFyO4zG7uIKt4Mp8jL0BUSIBr5c_9T8v_lswTw3sRr61UoY)

Enter the mobile code from your text, and for now, you'll have to retrieve your email code from customer.io, by making sure you are in the TEST environment and finding the email from the Delivery Log.

Next, you will be prompted to create a password.

![enter image description here](https://lh3.googleusercontent.com/fqrtA1UGSYYH1mixKZR8-uygUojVA6hzF79V-86GCcRiKu4y0xDLHRXPI-x8FyCs4nb2Sqvu7yml)

Once that's been done, you should be finished and now have a parent user account!

![enter image description here](https://lh3.googleusercontent.com/5fbKO0ETaotE7P-9zpT3K_3WlO6MBImKeWtJvOYse2KCNhpPsH-X8cuzSPYZUB8CsOKjXKOITb6d)



## Parent Validation

So once you've logged in with your new parent account, you should immediately be taken to this Validation screen. This is where parents have to answer "validations" in order to confirm their relationship to the student.

![enter image description here](https://lh3.googleusercontent.com/jkXzDimqvkge76GV9Op6ekmliiJPH3BrDYNEQhnw23120JEUffdLpxOv3iBVaQk1-imNUbbcXx4)

You can choose to submit the answers or skip the validation (if you don't care about the student it's connected to, for example)

One you've completed these, one way or another, you will see a success screen.
![enter image description here](https://lh3.googleusercontent.com/BNb9TFIaY6C6w8ypgpmfzP6X-f6nN1ACWDtrwzxajyNDqtK51jmJG5SfqfHNx39mGNYneBiEDlE)

Any time you log in or reopen the app and do NOT have a verified validation, you will see this screen. If you DO have a verified validation, you will be taken to the main app.

## Parent App

So far, there is not much for the parents. The student card has not yet come to fruition, so stay tuned for that. Here is the current view that parents are taken to upon being verified.

![enter image description here](https://lh3.googleusercontent.com/xqQpfCAfSkTGsBSvF3lY6AGZ-U6CF5ONlG7IqRW3QKli4RtRVSqUD0X6k9dN4jDlyNLXH5GIrUA)

You can also text as a parent as well.

![enter image description here](https://lh3.googleusercontent.com/HOU-ckUwQDIpYeEEPO9u6wUO9S89jlEz1dl6jFJLJxPxgFJUP7PCE4XMAM6L78g-Isx_3CtquL8)


