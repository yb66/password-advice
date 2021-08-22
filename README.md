# Never be hacked again

Give yourself 30 minutes to get this all sorted. It's not hard, just follow each part, don't skip any.


### In short:

The number one way to be hacked is to have a bad password and then to use it (or variations of it) on more than one service. So, to fix your security you:

1. Get better passwords
2. Don't reuse them

### The slightly longer strategy

You are going to construct two 🔑🔑 *very strong* master keys that are also *very memorable*. One is to lock your email account, the other locks a digital safe. Then you are going to make *throwaway keys* for every service you use, *put them in the safe*, and *only unlock it when you need one*. You will not be able to remember the throwaway keys but *it doesn't matter*, you have them. If someone guesses or steals a key from a service then none of the other keys will be compromised. That's how it works.

What that means in practice:

1. You create 2 memorable, strong passwords (how to do that is below)
2. Use one to secure your email account, it is the most important thing to secure. If an attacker has your email they have everything 😱
3. Get a password manager and use the other memorable, strong password for it 💪
4. Change your passwords for Instagram, Facebook, Yahoo etc using the password manager.


A nice side-effect is that updating your password in Gmail and Instagram will kick out anyone logged in on another device.


### To begin, create 2 strong and memorable passwords

#### This is how it's done:

1. You'll need a die (dice) 🎲
2. Roll it 5 times.
3. Pick the word off the list for that number.
4. Do it again, probably at least 5 times is good.

An English word list is [here](https://www.eff.org/files/2016/07/18/eff_large_wordlist.txt) 

A Japanese word list is [here](https://raw.githubusercontent.com/yb66/diceware-ja/master/wordlist.csv)

For example:

I roll…

14335, that is *bulb*  
41461, that is *mug*  
43553, that is *pardon*  
56214, that is *starlight*  
12152, that is *antonym*  

My master password is **bulbmugpardonstarlightantonym**.

This would take *centuries* to crack.

If you don't like the words then roll again, just *don't pick them yourself*, let the dice choose. If you don't like the format, change it, e.g.

*BulbMugPardonStarlightAntonym* or *bulb-mug-pardon-starlight-antonym*, whatever suits you best is best, it's your password!

By the way… I showed my mum how to do this, she is over 70, she was worried it wouldn't work, she told me later that it was easy!

### Now, WRITE IT DOWN!

You were told never to write down a password, right? That was stupid.

Write it down, put it somewhere *safe* (not stuck to a screen on a sticky note, *actually* safe). Write it down again and put it somewhere else, like your mum's house. Soon you will not forget it but **don't take chances!**

### Do it again

That's right, you'll need two.

One for your email.

One for your safe that will keep all the other passwords.

Again, write it down twice. Keep it in a safe place and give the other copy to your mum to keep somewhere. Lose them and you'll cry 😭

My second attempt produces:

25555	*erupt*  
52452	*ruined*  
52635	*sandal*  
23164	*devious*  
16136	*clerk*  

### Securing Gmail<a name="change-email" />

I'm going to assume you have a Gmail account.

1. Log in
2. Go to settings (the cog ⚙ in the top right)
3. Click *See all settings*

![Screenshot 2021-08-22 at 17 41 02](https://user-images.githubusercontent.com/326444/130543816-822cec29-71ce-4f99-a8e7-850749090fb7.png)

4. Select *Accounts and Import* then click *Change password* - you'll be redirected to Google's accounts page

![Screenshot 2021-08-22 at 18 57 14](https://user-images.githubusercontent.com/326444/130545923-fcf6cca5-a93a-4ce6-9f0f-ae525802cc60.png)

6. Just beneath the password section is *Ways that we can verify that it's you*. Make sure that the settings are correct - has the attacker put their details in?
7. Click the password arrow

![Screenshot 2021-08-22 at 17 43 06](https://user-images.githubusercontent.com/326444/130546926-3eb79dc9-30f6-4422-bdbf-c944646e8f77.png)

8. Enter in your new password
![Screenshot 2021-08-22 at 17 56 22](https://user-images.githubusercontent.com/326444/130349782-42d1b9b0-69f4-4b17-8d92-dc49e5a0ebd7.png)

No one but you is in your email account now 🥳🥳🥳

### Get the safe i.e. password manager

I recommend Bitwarden, it's free, reputable, and lots of people use it (including me). It's more convenient than the Apple Keychain too, in my opinion.
 
[Go to their website and register using the other master password you made](https://vault.bitwarden.com/#/register).

So in my example I would use *eruptruinedsandaldeviousclerk* here:

![Bitwarden register form](https://user-images.githubusercontent.com/326444/130617864-db0e6ebf-16f2-4b28-9a1d-637862c49c94.png)

Then [download Bitwarden here](https://bitwarden.com/download/) for phone (and later you'll want to get the desktop client and web browser plugin too).

Next! Log in to Bitwarden on the phone:

![Logging in to Bitwarden phone](https://user-images.githubusercontent.com/326444/131205631-48f36636-f7e2-4f05-969f-d37e67d26950.PNG)

Excuse my fat finger attempt, I was trying to take a screenshot 😅

This is my main screen, yours will be similar (but empty).

![Main vault screen](https://user-images.githubusercontent.com/326444/130619905-b7fb0bc0-37eb-4719-835e-641f971834aa.PNG)

Click the plus-sign ➕ in the top right to add your first item. Fill in the *name* (e.g. "Main Insta account" or just "Instagram", something like that) and your Instagram *username*.

When you get to *password*, click on the circular arrows to the right.

![Add an item to Bitwarden](https://user-images.githubusercontent.com/326444/130620280-af9ccbf1-81ab-4e7c-8f1c-ee48d1cf562a.PNG)

Here, Bitwarden will generate a password for you. These are my settings:

![Generate a password in Bitwarden](https://user-images.githubusercontent.com/326444/130622060-eeebd99e-965e-48c7-8dfc-3abfcfcd0bf9.PNG)

Click *Select* in the top right and it will take you back to the last screen.

Fill in the URI field like so:

![Add a URI to the item in Bitwarden](https://user-images.githubusercontent.com/326444/130622563-07557741-4d51-44c7-af57-d7161a34f8e3.PNG)

Click *Save* in the top right.

### One more thing

Click *Settings* in the bottom right.

![Bitwarden set touch id unlock](https://user-images.githubusercontent.com/326444/130628462-65b55c32-a29d-4d8c-858e-1f01d4dd8843.PNG)

Then make sure *Unlock with Touch ID* is enabled.

![Bitwarden set touch id unlock](https://user-images.githubusercontent.com/326444/130627767-edd9907d-564f-4db9-abb3-28b22195d435.PNG)

### Next step, iphone settings

Click out of Bitwarden and go to the iphone settings:

![iOS-Settings-icon](https://user-images.githubusercontent.com/326444/130623458-d4e5b93e-ce2e-409b-941f-c4ce6a8b569f.png)

Go to *Passwords & Accounts*

![iphone General settings](https://user-images.githubusercontent.com/326444/130623210-bfc21956-6d15-41d9-b76c-216d361366b5.PNG)

Click *AutoFill Passwords*

![Settings passwords and accounts](https://user-images.githubusercontent.com/326444/130623205-25b39b0c-7f00-44e2-8c5a-b8f40be5ef0e.PNG)

I don't use the Keychain, you can use both if you want but I've moved completely to Bitwarden. Either way, make sure Bitwarden is ticked.

![Autofill passwords](https://user-images.githubusercontent.com/326444/130623197-7b8abf2b-085e-432f-abd2-ac7a7f8bdc53.PNG)

You can close the iphone settings now.

### Changing the Instagram password

Open Instagram, go to your account main page, click the settings 𑁔 in the top right and then *Settings*

![Instagram opening settings](https://user-images.githubusercontent.com/326444/130625632-b3b702fb-0eba-4918-b441-78872ce85d90.PNG)

Select *Security*

![Instagram Security settings](https://user-images.githubusercontent.com/326444/130625811-2f3014c0-0c55-4a06-a033-609a98c211af.PNG)

Here you can check the *Login activity* if you wish. You should see only yourself logged in.

![Instagram logged in devices](https://user-images.githubusercontent.com/326444/130632605-761d3447-d006-4972-ad3f-7a19ccfbbef9.PNG)

(I've never been to Chiyoda-ku but I'm in Japan, close enough 😂)

Go back to the Security page.

Click *Password*

![Instagram password security](https://user-images.githubusercontent.com/326444/130626513-7cd5a136-e281-44f3-952e-2e9c218ea5da.PNG)

Put in your old (current) password.

![Changing Instagram password](https://user-images.githubusercontent.com/326444/130626708-26f2af44-fe5d-48bb-9adc-92bd81b5236e.png)

Then switch over to Bitwarden (don't use that button on the screen right now, that's for future use, just switch over to the full app) and click on the Instagram entry (it's the only one!)

Then *copy* the password using the little squares-symbol:

![Copying insta password](https://user-images.githubusercontent.com/326444/130628962-2194436c-8b07-49aa-862f-65903ba4346f.PNG)

Go back to Instagram and paste it in to the 
*New password* and *Re-enter new password* fields. Hit *Save* in the top-right.

This will also log out any other devices. You are now safe!!! 🥳🥳🥳

### 2nd factor authentication

If you get this far then let me know and I'll add a section on how to do this (everyone should, in my opinion). If you decide to set it up yourself, never use text messages for this, they're not secure any more… 😓

### If you want to check whether your password may have leaked

[Go to this service, HaveIBeenPwned](https://haveibeenpwned.com/) and put in your email and/or phone number and it'll tell you if your account has been involved in a service's data breach.

***Don't use the password checker service they offer!*** I do trust this service but not *that* much - never give out your master passwords!!!!
