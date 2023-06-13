# What’s the Difference Between Windows and Windows Server? Notes
## What is a server, and how is it different from a regular computer? How would you describe this difference to a friend who doesn’t know much about computers?
-  Microsoft designed Windows 10 for use as a desktop you sit in front of, and Windows Server as a server (it’s right there in the name) that runs services people access across a network. While Windows Server does have a desktop option, Microsoft recommends installing Windows Server without a Graphical User Interface (or removing it), leaving just a command line to work which reduces the overhead needed to run the server.
## How does the way Windows Server receives updates differ from Windows Home and Pro?
- The way Windows Server receives updates differs from Windows Home and Pro in terms of release schedule, update management, and the type of updates offered. Windows Server follows a more controlled and predictable update cadence, emphasizing stability and reliability for enterprise environments. The updates are thoroughly tested and released in specific cycles, allowing IT administrators to plan and manage the update process.
## Does Windows Server have different hardware requirements than Windows Home or Pro?
- Yes, absolutely. Windows server is meant to handle a lot of proccesses, way higher than a desktop. 
- Windows Server also supports more powerful hardware. While Windows 10 Pro has a max limit of 2 TB of RAM, Windows Server allows for 24 TB. A desktop user is unlikely even to consider such a large amount of RAM, but servers can make good use of their greater RAM capacity, between managing many users, computers, and potential VMs through Hyper-V.

- Windows 10 has a limit on processors as well. The Windows 10 Home edition only supports one physical CPU, while Windows 10 Pro supports two. Server 2016 supports up to 64 sockets. Similarly, a 32-bit copy of Windows 10 only supports 32 cores, and the 64-bit version support 256 cores, but Windows Server has no limit for cores.

- To get something closer to these capabilities, you would have to use Windows 10 Pro for Workstations, which supports 4 CPUs and 6 TB of RAM.

### Source: ("What’s the Difference Between Windows and Windows Server?" Josh Hendrickson, https://www.howtogeek.com/404763/whats-the-difference-between-windows-and-windows-server/)
