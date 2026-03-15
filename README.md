# EA-1-Sentinel-s-Watch-
This is my submission for EA-1 for 427

Activity Description: The expectation was to complete a cyber security capture-the-flag contest using skills such as reverse engineering, password cracking, wireless cracking, Linux fundamentals, and more. During this event, I showcased my ability to crack weak hashes using dictionary attacks and crack certain cryptographic problems using my knowledge. Our team consisted of 4 people, William Fralia, Aaron Aytes, Taylor Tran, and me. We worked remotely while on a video call. 

Technical decisions: The technical decisions I took to solving some problems in this event was using certain software and commands to achieve the best result for my problems. For example, one of the problems given to me was a problem that required combining multiple bin files as well as using a hash to unlock the combined bin files. By using simple linux functions such as ‘cat’, I was able to concatenate the files to give me the combined and reconstructed zip file of all the binaries. I then used the given sha256 key to open the zip and was given a pcap file. I chose to run ‘hcxpcapngtool’ to see if the pcap file would give me a certain string that I could then use to crack using hashcat. I used a general word list called ‘rockyou.txt’ and then began finding the proper password. It gave me a broken hash and the answer turned out to be ‘ironspider’.

Contributions: Since this was a ctf, everyone was responsible for answering certain questions on the ctf webpage. For example, as I began solving the oopsec problems, some of my other teammates began solving the wireless cracking problems or basic linux problems. Each of us were responsible for solving as many problems as possible within the time frame. 

Quality Assessment: I would say that I put in a good amount of effort into this event in the sense that I spent my time well delegating my time for certain tasks. If I were to redo this event again, I would definitely spread my time and effort across multiple problems rather than scoping down my targets to one single problem. 


