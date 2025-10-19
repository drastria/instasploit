Instasploit is an Shell Script to perform multi-threaded brute force attack against Instagram, this script can bypass login limiting and it can test infinite number of passwords with a rate of about 1000 passwords/min with 100 attemps at once.

## Legal disclaimer:
Usage of Instasploit for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 

![Instasploit](https://github.com/user-attachments/assets/0fbc23f4-a8ca-42ee-bea9-d9aa48ade988)

### Features
- Multi-thread (100 attempts at once)
- Save/Resume sessions
- Anonymous attack through TOR
- Check valid usernames
- Default password list (best +39k 8 letters)
- Check and Install all dependencies

### Usage:
```
git clone https://github.com/drastria/instasploit
cd instasploit
chmod +x instasploit.sh
sudo ./instasploit.sh
```

### Install requirements (Curl, Tor, Openssl):

```
chmod +x install.sh
sudo ./install.sh
```

### How it works?

Script uses an Android ApkSignature to perform authentication in addition using TOR instances to avoid blocking. 
The script uses Instagram-py algorithm (Python).

### Donate!
Support the authors:

[![Donate using Trakteer](https://new.trakteer.id/_assets/v11/f005987b6b7970f1696c6a8e2306d192f63a03ae.png)](https://trakteer.id/drastria/gift)
