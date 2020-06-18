
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


# Internet Architecture 

## Internet Protocol
What is an IP address and what is the difference between IPv4 and IPv6?  
 An IP address is a series of numbers that identify a device connected to a network. IPv6 allows for vastly more available numbers, meaning more devices able to be connected.


Find the IP address of your computer by typing ipconfig at the command prompt (refer back to the "Operating Systems" module for details.) Take a screenshot of the command without including the IP address to show your success, name the file ipconfig and upload to the lab folder on GitHub. 
 

What is ICANN and how do they contribute to the global Internet?
the Internet Corporation for Assigned Names and Numbers is a caretaker for the databases and namespaces of the internet.

## TCP/IP

What is the responsibility of TCP/IP? 
The TCP/IP makes sure that methods follow protocol, allowing for efficieny and a more unified global internet ( or more restrictive one depending on where you are based)

Explain how the client-server model applies to TCP/IP. 
 The IP address contacts the computer which then creates an extension to its next point. in TCP/IP there is the same idea once it connects to the user's IP, where it can then traverse a larger playing field than the local network. 

 
Review the section of the article aligning the post office with protocol stacks.  Why are layers important to changing technology? 
Layers can be changed out/altered without heavily impacting other layers, or sections of the process.


What types of applications run on the "application" layer? 
items such as HTTP, SMTP, POP3.

## Internet Security

What is HTTP and how does it support the client-server model? 
HTTP allows for visualization of web pages. This information goes from the user's device (client) into the public internet (server).

Explain the protocols that secure HTTP uses to protect data. 
Secure HTTP puts encryption on the data.

##  Securing Your Web Browser
Why should you secure your browser? 
The internet is essentially the wild-west all over again. With all the freedom and information available, it is not difficult for scammers and hackers to trick and manipulate a user into giving sensitive information.

Explain one of the risks described in the article.
Cookies store data to your system regaring websites visited and are taken away after a specific event or time expiration. They are risky as they allow the website to also gain access to who exactly is accessing their site. Some may consider this an evasion of privacy.
