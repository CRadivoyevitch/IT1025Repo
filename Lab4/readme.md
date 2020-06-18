
# Cybersecurity and Encryption 

magine you are part of the Amazon.com online chat. Explain how each component of the security triad would impact your job 
 Integrity: If the online chat is not helpful, or is performed by obvious bots, the user will realize this and be less enticed to use the platform again
 Availability: If the chat is not available 24/7 then user questions will be missed and the company will lose potential sales
 Authentification: I someone is attempting to access personal information, they could very well be learning it for ill means

Identify three daily tasks that require authentication. Explain how each one could be converted to multi-factor authentication 
 1.I currently need to put in a password when unlocking my phone. Having the fingerprint or facial recognition unlock feature appear after the password was entered would further ensure my safety.
 2.I am logging into my work computer, but just a username and password is not safe enough. Using an app on my phone that presents a constantly changing code provides increased security
 3. When I attempt to log into my brother's video game account I may know the password, but if the device is different I am prompted with a confirmation email that is sent to the account it is linked with. This keeps things secure as a multi-factor authenticator.

Explain ACL and RBAC. What are the advantages and disadvantages of each?  
 An Access Control List is easy to create but difficult to edit Each user is linked to what role(s) they have. While more complicated to make, the Role-Based-Access Control method gives a title depending on the roles available, and then addresses that title to the user, making it easier to promote or demote a user.

Explain the interaction of ciphertext, a public key and a private key 
 The Public Key encodes a message into its ciphertext, or hidden code. It is then transfered to the other end where a private key deciphers the message back to its original form.

Explain why we need public key cryptography
There is always the ability to intercept or eavesdrop on information being transmitted on the internet. Having public key cryptography allows for the two ends to have a hidden element that causes the third party to be unable to access the information, something obviously important or security

## Cryptography 
I chose to write a short pangram in an attempt to defer the frequency analysis. Most perfect pangrams are jibberish however, and so this message may very well be crackable.
The coded message is hnbepiwxoxcv ldjas uxm fjpztg dqytrixkth, or sympathizing would fix quaker objectives.
 
 Polyalphabetic ciphers are such where they act like Ceaser's cipher but utilize a secret shift word that helps flatten the frequency distribution.
 
Type a message in the "Frequency Fingerprint Exploration" box and explain the result.  Would it be different for different languages?  
 The result is much like the boxes predicted. This is not different for other languages under Zipf's Law.
 
Type a message in the "Polyalphabetic Exploration" box as well as a shift word.  Explain the result. 
I used the same message as before, with shift word angel. The result is
tmtumuvpeuou dtgmr mnj rihpqa cioqdhpaqt. The distribution is indeed flatter and shifted.
 
## Brute-Force 
What is Brute-Force and how does it relate to Kerckhoffs's principle?
Brute-Force is simply trying every combination until one works. Kerchkoffs's principle says that a code is unbreakable unless they have the cipherkey for it which generally holds true, although some keys are easier to gain than others.
