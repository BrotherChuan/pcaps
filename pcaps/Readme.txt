set1
1.There are 1503 packets in this set.
2.File Transfer Protocol(FTP) was used.
3.FTP is insecure because both passwords and data are not encrypted.
4.Secure Shell Protocol is the secure alternative to FTP.
5.67.23.79.113
6.Username: ihackpineapples  Password: rockyoul
7.4
8.BjN- OlhCAAAZbiq.jpg , BvgT9p2IQAEEoHu.jpg , BvzjaN- IQAA3XG7.jpg , smash.txt

set2
10.There are 77882 packets in this set.
11.There is only one plaintext username-password pair.
12.Using ettercap by command: sudo ettercap -T -r set2.pcap | grep¡±PASS¡±.
13.For USER: chris@digitalinterlude.com PASS: Volrathw69, the protocol is POP, server IP is 75.126.75.131, port 110. 
14.One.
15.Filter out IP 75.126.75.131 in wireshark and follow TCP stream to check if this pair go through:
     	+OK POP3 server ready <aece765e-be1e-4e0d-a4ab-e4cb003228d7@mail.si-sv3231.com>
    	USER chris@digitalinterlude.com
    	+OK User:'chris@digitalinterlude.com' ok
    	PASS Volrathw69
    	+OK Password ok
   Thus, chris is legit.
16.Avoid to join unknown wireless connections or at least do not log into servers using unencrypted protocol (like HTTP) when connecting to them.