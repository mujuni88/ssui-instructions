# Testing Parent Verification

Step by step instructions on how to verify a parent user in our app.

## Testing Instructions

- Log in as a superuser or district admin (**anytown@bcg.io is fine**), and click the **Parent Access Management** module link on the left.

![Parent Access Panament](https://lh3.googleusercontent.com/6GeyF80T_US54b46kn_KD3HWp5a1Alh3hxkxSKbnizuJB84x248oz5bWVVrrRrnvmWnXon-DD8g)

- **Find the contact** that has **your email** and **your phone number** and add yourself as a parent user.

![enter image description here](https://lh3.googleusercontent.com/GhNcLdVi_17M5m-Wt70g1i_4-Vl60rYD9SH6KTz7ZRf3gijtOrq7f_BALgggFOjlY6u1VCdno0s)


- In production, parents will receive an email with a link to verify on the web and a text to verify on the mobile app. On our staging setup, however, emails do not work, so you will need to get the email sent to your new potential user account from **customer.io**. In the email, **copy the email verification code** and then click the button that should take you to the verification page.

![enter image description here](https://lh3.googleusercontent.com/1ttvAMyT4areVXdvi343pW6lXbx86zYKh3dsKTjCtY40F7bN_y40FE99AecdaHZMqYBKmUlFeqM)


- Upon arriving at the verification page, you should be greeted with **two fields** for entering your **email verification code** and your **phone verification code**.  Paste the email verification code into the appropriate field and grab your phone verification code from your text messages, and do the same with it.

![Verification Home](https://lh3.googleusercontent.com/dOHbisHTNP4mizxvnhxyVnThlCXrSv_dNESqzcMITYBVnQWjuF3ZFD4KE_rFnntmqLXlo9A1HO8)

- You should arrive on a screen for creating your account password. Go ahead and fill this out (one field for **password creation** and one for **password confirmation**.)

![Create a password](https://lh3.googleusercontent.com/68Khft5uLlP4sEMCNw_t1NxCMHqeaRAPt7pb4c4mbul-fwz0t9gGNwTtIyuDwge5DxxYY3Tp6tw)

- Next, you will be **redirected** to the main **login screen** and should be able to use your new parent account to log in!

![Final step](https://lh3.googleusercontent.com/gYsGYJ7GFJTretWHMo6IG2sNJsOtPW4nkCO_yQUzev01WyqHlDI0PEes9N13gsH7H8fYzqMadvw)
