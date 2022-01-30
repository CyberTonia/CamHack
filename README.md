# CamHack
Grab cam shots from target's phone front camera or PC webcam just sending a link.
![cheese](https://drive.google.com/uc?export=view&id=1JfeCw8ukW0b2jONaRYXj0Rl34e-h1pL7)

# What is CamHack?
<p>CamHack is techniques to take cam shots of target's phone front camera or PC webcam. CamHack Hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device</p>

## Features
<p>In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
   <li>Online Meeting [Beta]</li>
</ul>
<p>simply enter festival name or youtube's video ID</p>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Parrot Sec OS</li>
</ul>

# Installing and requirements
<p>This tool require PHP for webserver, SSH or serveo link. First run following command on your terminal</p>

```
apt-get -y install php openssh git wget
```

## Installing (Kali Linux/Termux):

```
git clone https://github.com/CyberTonia/CamHack
cd CamHack
bash camhack.sh
```

## Change Log:

<p><b>Version: 3.5:</b> Add new online meeting template</p>
<p><b>Version: 3.4:</b> Ngrok authtoken update</p>
<p><b>Version: 3.3:</b> Fix ngrok direct link</p>

