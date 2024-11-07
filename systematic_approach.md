# passive recon
---------------
nmap 10.50.27.164 -T4 -sV -vvvv -p21-23,80 -Pn

nc 10.50.27.164 22 each open port verify services
SSH-2.0-OpenSSH / 

go to that box through telnet or ssh 

[do host enumeration] (ip a / ip n / ip r / ss -ntlp {might determine that a specific port is ope that you didnt see from nmap} )

[tunnel 1] ssh user@BH1 -L 58800:BH1(loopback):80 -NT 

ip n | grep -v FAILED
defualt route is router you can skip routers


left off at between sokka and Aang dynamic port forwarding
need help with dynamic port 

for i in {1..254} ; do (ping -c 1 192.168.1.$i | grep "bytes from" &) ;done

proxychains nc 127.0.0.1 12345 | md5sum
|S-chain|-<>-127.0.0.1:9050-<><>-127.0.0.1:12345-<><>-OK
1889cfbd314121a790f9b89708ed8b67  -
student@blue-internet-host-student-16:~$ echo "Life happens wherever you are, whether you make it or not." | md5sum
681f14e00a06dc21f9d58c9024c8a674

eog 10.50.20.250/Sokka-http.png

ssh student@10.50.25.214 -R 50899:127.0.0.1:22 -NT

ssh Rick@127.0.0.1 -p 50899 -D 9050 -NT

