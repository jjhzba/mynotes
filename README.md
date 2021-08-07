# mynotes
1. Set a password or PIN --
Setting a password or PIN on your device is an excellent way to prevent someone else from using it or accessing the information you’ve stored on it. Pick a password that’s hard to guess

2. Enable the screen’s auto-lock function --
This prevents someone from picking it up and using it without your knowledge.  

3. Update Your Operating Systems Regularly --
make sure you have automatic software updates turned on by default on your mobile devices. Regularly updating your operating system ensures you have the latest security configurations. 

4. Stay secured --
users shall be required to exercise due care and follow requirements to protect Mobile Devices against the risk of loss, damage, theft, malicious code, or data or application compromise, and promptly report any such incidents to IT

5. device usage --
only in Office, can't take back home. lock it into secure place after work

6. Creating backups routinely --
send wechat logs to mailbox daily

7. exception or emergence --

8. reference standard --

1. 可以发送到syslog-ng存为日志
2. 但是splunk无法使用windows addon解析出正确的field，如像SID等，只能作为普通日志存储功能使用
3. IMS的服务器和PC一共大约有180台左右，由于无法像splunk agent过滤不必要的日志，每天日志量大概有30G左右
4. 这样须额外增加硬盘和license
5. 每天180台的日志要手工放到不同的机器目录下，工作量大且易出错
6. Splunk ES也无法正确分析，无法起到相应的作用
7. 即使作为一个短期的解决方案，也是费人力，物力和财力；长期更不推荐
8. 最好在IDF安装splunk服务器
