contact me if your an actual researcher and i will give you the full code to analyze if you want

The backconnect server supports multiple connections and is made in QT and supports proxy connections to the victim.

Also all the drivers can be either signed on panel side (supports multiple EV certs) or you can have test mode.

Everything mentioned here is for eductional purposes and everything is purely fictional. I purposely redacted a lot of code and messed stuffs up since im a pussy and dont want this to be used to cause any real harm.


What is in here:

Kernel mode rootkit, does not trigger KPP, uses callbacks. redacted hidden VFS code. But there is a filter code to prevent access. 

UEFI based rootkit - from scratch does not use any public lib (i am not going to release this for personal purposes and also does not bypass secure boot)

Kernel mode 


Usermode Bot Features:

Send files to block access to driver.

Send registry keys to block access to driver.

Track  1/2

Back Connect that can start:  desktop or reverse socks5 (UI made in QT)

 Desktop - the actual code uses win32u undocumented functions

Reverse Socks5


DH key exchange for AES.

Communicates with AFD.sys for networking. Has chunked reply praser.


PHP Code:

No framework needed.

Has server sided based polymorphism for driver. 


Register as service





In Conclusion:

I am not reponsible for any losses or damages of any sort. This is all purely educational and I made this a long time ago.



