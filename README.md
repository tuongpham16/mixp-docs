# mixp-docs
Add a sysctl file in /etc/sysctl.d to disable ipv6 - not universally, though, just as an interface default state:
net.ipv6.conf.default.disable_ipv6=1
<br/>
curl -SL -o px-install.sh https://github.com/tuongpham16/mixp-docs/releases/download/1.0/px-install-arm64.sh
<br/>
UPDATE 1.2: curl -SL -o update.sh https://github.com/tuongpham16/mixp-docs/releases/download/1.0/px-update-v1-2.sh && bash update.sh
