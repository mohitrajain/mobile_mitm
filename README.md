# mobile_mitm
## This is an experiment on how to intercept mobile data on a network using a proxy server .

## This report shows how to check data usage by mobile applications / mobile operating system and predicts how privacy can be voilated . This is small experiment you can extend it on large scale and for more protocols like xmpp etc .

### Basic insights :
### 1. The tested mobile is configured to use our proxy server . 
### 2. I used iptables to create accept proxy connections . ( iptables is also used for transparent proxy )
### 3. I have chosen Burp suite as my intercepter/proxy . ( only Http and https traffic is monitored this way )
### 4. I also generated a self signed ssl certificate using openssl and then installed it in user's mobile .
### 5. The same certificate was also installed in Burp suite so that it can decrypt all the ssl traffic .

## Note :- we can also use squid proxy server in transparent mode to intercept mobile data.

# Full blown steps of mitm and report on mobile privacy is present [here](https://github.com/mohitrajain/mobile_mitm/blob/master/mobile_privacy.pdf).
 
## Note :- all ids , macs , imei numbers are spoofed .

# Disclaimer :
### 1. All the statements made in the report are my personal views .
### 2. The mobile chosen here is a random one . So all the url shown in the mobile are totally random . There was no intention of pointing any particular company or url .
### 3. This report is for study/research purposes only . All the comments present here are mine and this report contains my personal view on privacy .

### If you find anything unappropriate please create an issue for the same or you can mail me perosnally .
