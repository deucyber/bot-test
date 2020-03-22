
new day new post everyone

**a bold text**

*emphasized text*

## Heading

~~strikethrough text~~

 - List item
 - another list item here
 
 
 - [x] this one's with a checkbox
 - [ ] without check

> Blockquote

|  some| shit  |
|--|--|
|  here|  blob|

![actual image](https://i.hizliresim.com/Zykjpe.png)
[goes to the pic source](https://imgur.com/a/4aJbAwJ)


    if yontem == 1:
	    arpbaslik = ARP(hwsrc=fake_mac , psrc=my_ip , hwdst=target_mac , pdst=target_ip , op=1 )
	    paket = ethbaslik/arpbaslik
	    while True:
	    sendp(paket)
	    time.sleep(5)
    elif yontem == 2:
	    arpbaslik = ARP(hwsrc=fake_mac , psrc=my_ip , hwdst=target_mac , pdst=target_ip , op=1 )
	    paket = ethbaslik/arpbaslik
	    sendp(paket)
	    arpbaslik = ARP(hwsrc=fake_mac , psrc=my_ip , hwdst=target_mac , pdst=target_ip , op=2 )
	    paket = ethbaslik/arpbaslik
	    while True:
	    sendp(paket)
	    time.sleep(5)