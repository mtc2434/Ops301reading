# What is a Windows Domain and How Does It Affect My PC? Notes
## Explain the role of a Domain Controller?
- This means you can log in with the same username and password on any computer joined to the domain.
- Windows domains provide network administrators with a way to manage a large number of PCs and control them from one place. One or more servers — known as domain controllers — have control over the domain and the computers on it.
-Network administrators can change group policy settings on the domain controller. Each computer on the domain will get these settings from the domain controller and they’ll override any local settings users specify on their PCs.

## What is the benefit of being able to login with the same username and password on any computer joined to the domain? What are the security risks?
- It makes it less complicated to have to login to different computers with different usernames and passwords. Time efficient. The security risks are a lot bigger though. If someone finds out the password, they have access to the domain
## Describe how group policies are used in domains?
- All the settings are controlled from a single place. This also “locks down” the computers. You probably won’t be allowed to change many system settings on a computer joined to a domain.
- In other words, when a computer is part of a domain, the organization providing that computer is managing and configuring it remotely. They have control over the PC, not whoever is using it.

## In what other ways can you think of that domains could be used beyond what was presented in the reading?
- Maybe You can section off certain departments and each department would have their own specific domain controller? if that is how it was set up of course. You could probably change the group settings so that certain employees can access different resources based on their job

### Source
("What is a Windows Domain and How Does It Affect My PC?" Chris Hoffman, https://www.howtogeek.com/194069/what-is-a-windows-domain-and-how-does-it-affect-my-pc/)

