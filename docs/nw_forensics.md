<!-- MarkdownTOC -->

- [Network Forensics](#network-forensics)
	- [Network Forensics Blogs](#network-forensics-blogs)
	- [Network Forensics and Wireshark on Twitter](#network-forensics-and-wireshark-on-twitter)
	- [Network Forensics Tools](#network-forensics-tools)
		- [WireEdit](#wireedit)
		- [Wireshark](#wireshark)
			- [Wireshark online learning](#wireshark-online-learning)
			- [Laura Chappell](#laura-chappell)
			- [Sharkfest](#sharkfest)
			- [Wireshark Slides](#wireshark-slides)
		- [Fiddler](#fiddler)
		- [Transum wireshark plugin](#transum-wireshark-plugin)
		- [Manuales de Wireshark](#manuales-de-wireshark)
		- [Wireshark 2.0](#wireshark-20)
		- [Network Forensics and Monitoring for MySQL and PostgreSQL](#network-forensics-and-monitoring-for-mysql-and-postgresql)
	- [DPI Deep Packet Inspection](#dpi-deep-packet-inspection)
		- [CapAnalysis](#capanalysis)

<!-- /MarkdownTOC -->

[![digital attack map](images/digital_attack_map.png)](http://www.digitalattackmap.com/)

[![do not use wireshark](images/dont_use_wireshark.png)](https://twitter.com/packetbomb)

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/2PJugZm7LqYEHq" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/raymondkao/network-infrastructure-tcpip" title="Network infrastructure - TCP/IP" target="_blank">Network infrastructure - TCP/IP</a> </strong> from <strong><a target="_blank" href="https://www.slideshare.net/raymondkao">raymondkao</a></strong> </div>
</div>
<br>

|[![hak5_video](images/hak5_video.jpg)](https://www.youtube.com/user/Hak5Darren)|[![packet_bomb_video](images/packet_bomb_video.jpg)](https://www.youtube.com/channel/UC6lijopn1t2ETukUSLDDqMA)|[![tech_firm_video](images/tech_firm_video.jpg)](https://www.youtube.com/user/thetechfirm)|[![sharkfest_video](images/sharkfest_video.jpg)](https://www.youtube.com/user/SharkFest2015)|[![laura_chappell_video](images/laura_chappell_video.jpg)](https://www.youtube.com/channel/UCPOqFa77z1Gfwbe5JZaFaig)|[![laura_chappell_video2](images/laura_chappell_video2.jpg)](https://www.youtube.com/user/thebitgirl)|
|:---:|:---:|:---:|:---:|:---:|:---:|

# Network Forensics
## Network Forensics Blogs
- [wireshark.org](http://wireshark.org/)
- [sharkfest.wireshark.org](https://sharkfest.wireshark.org)
- [wiresharktraining.com](http://wiresharktraining.com)
- [packetbomb.com](http://packetbomb.com/)
- [blog.packet-foo.com](https://blog.packet-foo.com)
- [LoveMyTool - Building an Open Community for Network Management and Monitoring](http://www.lovemytool.com/blog)
- [thevisiblenetwork.com](http://www.thevisiblenetwork.com)
- [packetlife.net](http://packetlife.net/)
- [Packet Pushers](http://packetpushers.net/)
- [The Networking Nerd](http://networkingnerd.net/)
- [sharkfest.wireshark.org](http://sharkfest.wireshark.org)
- [seguridadyredes.wordpress.com](https://seguridadyredes.wordpress.com/)

## Network Forensics and Wireshark on Twitter
- [twitter.com/LauraChappell](https://twitter.com/LauraChappell)
- [twitter.com/WiresharkNews](https://twitter.com/WiresharkNews)
- [twitter.com/wiresharktweets](https://twitter.com/wiresharktweets)
- [twitter.com/wiresharku](https://twitter.com/wiresharku)
- [twitter.com/seguridadyredes](https://twitter.com/seguridadyredes)
- [twitter.com/packetbomb](https://twitter.com/packetbomb)
- [twitter.com/PacketJay](https://twitter.com/PacketJay)
- [twitter.com/packetlife](https://twitter.com/packetlife/)
- [twitter.com/packetpushers](https://twitter.com/packetpushers)
- [twitter.com/networkingnerd](https://twitter.com/networkingnerd)
- [twitter.com/SharkFest_2016](https://twitter.com/SharkFest_2016)
- [twitter.com/NetBeez](https://twitter.com/NetBeez)
- [twitter.com/Securactivepv](https://twitter.com/Securactivepv)

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/iX44XIZafiw" frameborder="0" allowfullscreen class="video"></iframe>
</div>
<br>

<iframe src="//www.slideshare.net/slideshow/embed_code/key/2PJugZm7LqYEHq" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/raymondkao/network-infrastructure-tcpip" title="Network infrastructure - TCP/IP" target="_blank">Network infrastructure - TCP/IP</a> </strong> from <strong><a target="_blank" href="https://www.slideshare.net/raymondkao">raymondkao</a></strong> </div>

## Network Forensics Tools
- [Digital Attack Map. Top daily DDoS attacks worldwide 🌟🌟🌟](http://www.digitalattackmap.com/)
	- [radware.com: DDoS Handbook](https://www.radware.com/social/ddoshandbook/)

### WireEdit
- [WireEdit. First-Of-A-Kind and The Only Full Stack WYSIWYG Packet Editor Edit L2 - L7 with just a few clicks](https://wireedit.com/)

<div class="container">
<iframe width="420" height="315" src="https://www.youtube.com/embed/Mp1hpMOjk6c?rel=0" frameborder="0" allowfullscreen class="video"></iframe>
</div>
<br>

### Wireshark 
- [Optimal Wireshark Setup | Enhance Your Wireshark Experience](https://www.youtube.com/watch?v=F4l3CedRlJc)
	- [Switches And Tool Placement (by Tony Fortunato). Ubicación de las herramientas de análisis de tráfico en redes conmutadas (switched networks). Taps, span ports y hubs](http://www.lovemytool.com/blog/2014/06/switches-and-tool-placement-by-tony-fortunato.html)
- [Wireshark 101: Transmission Control Protocol, video tutorial](https://www.youtube.com/watch?v=iX44XIZafiw)
- [Tip: do not capture on a computer directly unless you understand the side effects and you can live with them.](https://blog.packet-foo.com/2014/05/the-drawbacks-of-local-packet-captures/) 
>Do not capture on local systems. Use SPAN ports and TAPs, if you have to. It’s the only way to get good readings. Unless you don’t care about frame sizes, timings, broken checksums, interference from other software you should not capture on a local system.
- [HTTP Basic Authentication with wireshark](http://www.networkcomputing.com/applications/http-basic-authentication-primer/d/d-id/1323331)
- [youtube: TCP Window Performance Analysis](https://youtu.be/N-n1n6WKmRs)
- [How Can the Packet Size Be Greater than the MTU?](http://packetbomb.com/how-can-the-packet-size-be-greater-than-the-mtu/)
- [INE.com training videos: Analyzing Packet Lengths](https://youtu.be/qsUaB36CVDw)
- [blog.cloudflare.com - The story of one latency spike](https://blog.cloudflare.com/the-story-of-one-latency-spike/)
	- [packetbomb.com: Case Study: All Web Pages Load Slooooowly 🌟🌟](http://packetbomb.com/case-study-all-web-pages-load-slooooowly/)
	- [Calculate HTTP response time in wireshark](http://www.thevisiblenetwork.com/2015/01/21/calculate-http-response-time-in-wireshark/)
	- [Diagnose slow connections with Wireshark](http://theitjuggler.com/how-to/diagnose-slow-connections-wireshark/)
	- [Toubleshooting with Wireshark: Detect HTTP Delays](http://youtu.be/5k16DWEnEGA)
	- [Troubleshooting with Wireshark: Detect TCP Delays (full video)](https://www.youtube.com/watch?v=YJRmh6L2Hls)
	- [Packet timing and Average IO Graph with Wireshark](http://www.lovemytool.com/blog/2014/09/documenting-why-its-slow-by-tony-fortunato.html)
	- [Calculate HTTP response time in wireshark](http://thevisiblenetwork.com/2015/01/21/calculate-http-response-time-in-wireshark/)
	- [Understanding Application Performance on the Network – Part VII: TCP Window Size](http://apmblog.dynatrace.com/2014/08/12/understanding-application-performance-network-part-tcp-window-size/)
- [Troubleshooting with Wireshark: Identifying SIP Errors](https://www.youtube.com/watch?v=bu6kpneLlFc)
	- [How to Capture and Debug SIP Packets from asterisk using tcpdump and Wireshark](https://www.youtube.com/watch?v=OFpQLyQxt84)
- [Julia Evans: tcpdump is amazing 🌟🌟🌟](http://jvns.ca/blog/2016/03/16/tcpdump-is-amazing/)
- [tecmint: 12 Tcpdump Commands – A Network Sniffer Tool](http://www.tecmint.com/12-tcpdump-commands-a-network-sniffer-tool/)
- [Ten Powerful Wireshark Filters 🌟🌟🌟](https://community.tribelab.com/mod/page/view.php?id=638)

<blockquote class="twitter-tweet tw-align-center" data-lang="es"><p lang="en" dir="ltr">i finally figured out that tcpdump is amazing. here&#39;s some of what I learned: <a href="https://t.co/OxqKocS3p3">https://t.co/OxqKocS3p3</a></p>&mdash; Julia Evans (@b0rk) <a href="https://twitter.com/b0rk/status/710334113421664256">17 de marzo de 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet tw-align-center" data-lang="es"><p lang="en" dir="ltr">tcpdump is a command-line packets sniffer or package analyzer tool...<a href="https://t.co/ECkBftFsaX">https://t.co/ECkBftFsaX</a> <a href="https://twitter.com/hashtag/Linux?src=hash">#Linux</a> <a href="https://twitter.com/hashtag/networking?src=hash">#networking</a> <a href="https://t.co/U31fQ1iC3c">pic.twitter.com/U31fQ1iC3c</a></p>&mdash; TecMint.com (@tecmint) <a href="https://twitter.com/tecmint/status/731765697328517120">15 de mayo de 2016</a></blockquote><script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/KtIsj2KHBVw?rel=0" frameborder="0" allowfullscreen class="video"></iframe>
</div>
<br>

<blockquote class="twitter-tweet tw-align-center" data-lang="es"><p lang="en" dir="ltr">our star: the packet! <a href="https://t.co/bwRaObb4ko">pic.twitter.com/bwRaObb4ko</a></p>&mdash; Julia Evans (@b0rk) <a href="https://twitter.com/b0rk/status/812445169446490112">23 de diciembre de 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet tw-align-center" data-lang="es"><p lang="en" dir="ltr">anatomy of a packet <a href="https://t.co/ZeLU8IJ6GR">pic.twitter.com/ZeLU8IJ6GR</a></p>&mdash; Julia Evans (@b0rk) <a href="https://twitter.com/b0rk/status/802554278808322048">26 de noviembre de 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

#### Wireshark online learning
- [Udemy.com: Wireshark Crash Course](https://www.udemy.com/wireshark-crash-course/)
- [Lynda.com: Troubleshooting Your Network with Wireshark](https://www.lynda.com/Wireshark-tutorials/Troubleshooting-Your-Network-Wireshark/366447-2.html) 

#### Laura Chappell
- [Laura Chappell's Top Videos](https://www.youtube.com/user/thebitgirl/videos)
	- [Wireshark Tip 10: Identify Separate TCP Conversations with TCP Stream Index (Laura Chappell)](https://www.youtube.com/watch?v=0dFndZwkDGY)
	- [Wireshark profiles](https://www.youtube.com/watch?v=pxxcuR7fwXM)
	- [PacketLife.net](http://packetlife.net/)
	- [Sharkfest 2013 - Wireshark Network Forensics (Laura Chappell). Seguridad con Wireshark: ejemplos de ataques de seguridad DDoS (macof, DNS), filtros, perfiles, coloreado de frames y tshark para trazas largas](https://www.youtube.com/watch?v=UXAHvwouk6Q)
	- [wireshark's colors, by Laura Chappell](http://bit.ly/nmapcolors)

#### Sharkfest
- [Sharkfest '14 Retrospective](http://sharkfest.wireshark.org/sharkfest.14/)
	- [How to Use Wireshark to Analyze Video](http://sharkfest.wireshark.org/sharkfest.13/presentations/PA-11_How-to-Use-Wireshark-to-Analyze-Video_Betty-DuBois.pdf)
	- [Sharkfest '14 presentation: Get started with HTTP Analysis](http://sharkfest.wireshark.org/sharkfest.14/presentations/B6-Get%20Started%20with%20HTTP%20Analysis.pdf)
	- [Tuning Win7 Using Wireshark’s TCP Stream Graph](http://sharkfest.wireshark.org/sharkfest.12/presentations/A-3_A-10_Tuning_Win7_Using_Wireshark_TCP_Stream_Graph_a_Case_Study.pdf)
- **One way to prevent DDoS attacks similar to macof is by blocking connections (SYN) going through the firewall with MSS=0 and WinSize=0.**
	- [Flood network with random MAC addresses with macof tool](https://tournasdimitrios1.wordpress.com/2011/03/04/flood-network-with-random-mac-addresses-with-macof-tool/)
	- ['itsoknoproblembro' Toolkit - The Beast that Beat Banks](http://www.ehacking.net/2013/01/itsoknoproblembro-toolkit-beast-that.html)
	- [HTCIA | High Technology Crime Investigation Association](https://www.htcia.org/)

#### Wireshark Slides

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/BMQBcziSVb99Tt" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/btohara/wireshark-11760386" title="Wireshark" target="_blank">Wireshark</a> </strong> from <strong><a target="_blank" href="//www.slideshare.net/btohara">btohara</a></strong> </div>
</div>
<br/>

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/pJQVaZgoLM0OfA" width="668" height="714" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/pemrkosa/wiresark" title="Wiresark" target="_blank">Wiresark</a> </strong> from <strong><a target="_blank" href="//www.slideshare.net/pemrkosa">Ade Tamin</a></strong> </div>
</div>
<br/>

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/3KnN8B9Zr24KDx" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/gilsinnj/network-packet-analysis-with-wireshark" title="Network Packet Analysis with Wireshark" target="_blank">Network Packet Analysis with Wireshark</a> </strong> from <strong><a target="_blank" href="//www.slideshare.net/gilsinnj">Jim Gilsinn</a></strong> </div>
</div>
<br/>

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/2WexyGlky6zcGh" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/yoramorzach/wireshark-ts-lecture-v100-06july2009" title="Wireshark Basics" target="_blank">Wireshark Basics</a> </strong> from <strong><a target="_blank" href="//www.slideshare.net/yoramorzach">Yoram Orzach</a></strong> </div>
</div>
<br/>

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/HwCKZrrIBETAEN" width="668" height="714" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/dgsweigert/wireshark-traffic-analysis" title="Wireshark Traffic Analysis" target="_blank">Wireshark Traffic Analysis</a> </strong> from <strong><a target="_blank" href="//www.slideshare.net/dgsweigert">Dave Sweigert, CISA, CISSP, HCISPP, PMP, Sec+</a></strong> </div>
</div>
<br/>

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/pctYh63S9FWBmk" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/thetechfirm/special-episode-of-lmtv-for-wireshark-20" title="Special episode of lmtv for wireshark 2.0" target="_blank">Special episode of lmtv for wireshark 2.0</a> </strong> from <strong><a target="_blank" href="//www.slideshare.net/thetechfirm">Tony Fortunato</a></strong> </div>
</div>
<br/>

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/114Pf0trjXxHRg" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/thetechfirm/2015-08-15-wireshark-tips-and-tricks" title="2015 08 15 LMTV Wireshark tips and tricks" target="_blank">2015 08 15 LMTV Wireshark tips and tricks</a> </strong> from <strong><a target="_blank" href="//www.slideshare.net/thetechfirm">Tony Fortunato</a></strong> </div>
</div>
<br/>

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/o1Ly99kjraaiEN" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/thetechfirm/2015-03-06-lmtv-wtf-http-webcast" title="2015 03 06 lmtv wtf http webcast" target="_blank">2015 03 06 lmtv wtf http webcast</a> </strong> from <strong><a target="_blank" href="//www.slideshare.net/thetechfirm">Tony Fortunato</a></strong> </div>
</div>
<br/>

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/9cRw07hx5YDY" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/thetechfirm/2015-02-24-lmtv-baselining" title="2015 02 24 lmtv baselining" target="_blank">2015 02 24 lmtv baselining</a> </strong> from <strong><a target="_blank" href="//www.slideshare.net/thetechfirm">Tony Fortunato</a></strong> </div>
</div>
<br/>

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/5Tm344hq2S55M9" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/akhileshbhura/walbergexpose-voip-problems-with-wireshark" title="Walberg-expose vo_ip problems with wireshark" target="_blank">Walberg-expose vo_ip problems with wireshark</a> </strong> from <strong><a target="_blank" href="//www.slideshare.net/akhileshbhura">Akhilesh Bhura</a></strong> </div>
</div>
<br/>

### Fiddler
- [Fiddler is an HTTP debugging proxy server that complements Firefox or Chrome devtools (F12 key)](http://www.telerik.com/fiddler)
	- [Fiddler, un proxy para depurar aplicaciones](http://www.vozidea.com/fiddler-proxy-para-depurar-aplicaciones)
	- [slideshare: Debugging with Fiddler](http://www.slideshare.net/idof/debugging-with-fiddler)

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/MoJJdezWYicCvT" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/idof/debugging-with-fiddler" title="Debugging with Fiddler" target="_blank">Debugging with Fiddler</a> </strong> from <strong><a target="_blank" href="//www.slideshare.net/idof">Ido Flatow</a></strong> </div>
</div>
<br>

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/8bEIQd1XsE8?rel=0" frameborder="0" allowfullscreen class="video"></iframe>
</div>
<br>

<div class="container">
<iframe src="https://player.vimeo.com/video/43659037" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen class="video"></iframe>
<p><a href="https://vimeo.com/43659037">Ido Flatow - Debugging the Web with Fiddler</a> from <a href="https://vimeo.com/ndcconferences">NDC Conferences</a> on <a href="https://vimeo.com">Vimeo</a>.</p>
</div>
<br>

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/qkuJ6juEUhQ?rel=0" frameborder="0" allowfullscreen class="video"></iframe>
</div>
<br>

### Transum wireshark plugin
- [TRANSUM Wireshark Plugin. Some Wireshark dissectors provide response time measurement values, but what gets measured is not ideal for performance analysis work](http://www.tribelabzero.com/transum)
	- [Wireshark Transum Quickstart (by Tony Fortunato)](http://www.lovemytool.com/blog/2014/08/wireshark-transum-quickstart-by-tony-fortunato.html)

### Manuales de Wireshark
- [Manual básico de wireshark](http://www.slideshare.net/DIANYSS2012/manual-bsico-de-wireshark)
- [Analisis de red mediante Wireshark y Tcpdump](http://www.slideshare.net/JavierMartinRivero/analisis-de-red-mediante-wireshark-y-tcpdump)
- [Protocolo dns analizado con wireshark](http://www.slideshare.net/jopa001/protocolo-dns-con-wireshark)

<div class="container">
<iframe width="420" height="315" src="https://www.youtube.com/embed/UXAHvwouk6Q" frameborder="0" allowfullscreen class="video"></iframe>
</div>
<br>

<div class="container">
<iframe width="420" height="315" src="https://www.youtube.com/embed/N-n1n6WKmRs?rel=0" frameborder="0" allowfullscreen class="video"></iframe>
</div>
<br>

<blockquote class="twitter-tweet tw-align-center" data-lang="es"><p lang="en" dir="ltr">Learn to write <a href="https://twitter.com/hashtag/Wireshark?src=hash">#Wireshark</a> dissectors at <a href="https://twitter.com/hashtag/SharkFest16?src=hash">#SharkFest16</a> <a href="https://t.co/krDz2SPD0R">https://t.co/krDz2SPD0R</a></p>&mdash; Laura Chappell (@LauraChappell) <a href="https://twitter.com/LauraChappell/status/705404824234434560">3 de marzo de 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet tw-align-center" data-lang="es"><p lang="en" dir="ltr">A Deep Dive Into DNS Packet Sizes: Why Smaller Packet Sizes Keep The Internet Safe <a href="https://t.co/9a8duqMk5j">https://t.co/9a8duqMk5j</a> <a href="https://twitter.com/hashtag/networking?src=hash">#networking</a> <a href="https://twitter.com/hashtag/security?src=hash">#security</a> <a href="https://twitter.com/hashtag/sysadmin?src=hash">#sysadmin</a></p>&mdash; nixCraft (@nixcraft) <a href="https://twitter.com/nixcraft/status/705859377907920896">4 de marzo de 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>


### Wireshark 2.0 
- [Wireshark 2.0 Follow TCP Stream (by Tony Fortunato)](http://www.lovemytool.com/blog/2016/03/wireshark-20-follow-tcp-stream-by-tony-fortunato.html)

<div class="container">
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/qZL8kNj0E-A?rel=0" frameborder="0" allowfullscreen class="video"></iframe>
</div>
<br>

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/xPgCZwj446o?rel=0" frameborder="0" allowfullscreen class="video"></iframe>
</div>
<br>

### Network Forensics and Monitoring for MySQL and PostgreSQL
- [VividCortex](https://twitter.com/VividCortex)
- [Announcing VividCortex's Free Network Analyzer Tools for MySQL and PostgreSQL](https://www.vividcortex.com/blog/2015/05/13/announcing-vividcortex-network-analyzer-mysql-postgresql/)
- [Analyzing PostgreSQL Network Traffic with vc-pgsql-sniffer](http://www.pgconfsv.com/sessions/analyzing-postgresql-network-traffic-vc-pgsql-sniffer)
- [Wireshark Profile for Databases](https://www.facebook.com/notes/network-detectives/wireshark-profile-for-databases/1111610672263396)

## DPI Deep Packet Inspection
- [Deep Packet Inspection](https://en.wikipedia.org/wiki/Deep_packet_inspection)

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/gG1qW3XlNbQ?rel=0" frameborder="0" allowfullscreen class="video"></iframe>
</div>
<br/>

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/aDnpS0LhUC8?rel=0" frameborder="0" allowfullscreen class="video"></iframe>
</div>
<br/>

<!-- eliminado de slideshare:
<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/rPzpzxBYbllrNi" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/sandeshsawant3/deep-packet-inspectionteachnologyoverview" title="Deep packet inspection_teachnology_overview" target="_blank">Deep packet inspection_teachnology_overview</a> </strong> from <strong><a href="//www.slideshare.net/sandeshsawant3" target="_blank">Sandesh Sawant</a></strong> </div>
</div>
<br/> -->

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/7hWEt8tngimWMj" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/DanielVinyar/dpi-tech-evolutionv12" title="Deep Packet Inspection technology evolution" target="_blank">Deep Packet Inspection technology evolution</a> </strong> from <strong><a href="//www.slideshare.net/DanielVinyar" target="_blank">Daniel Vinyar</a></strong> </div>
</div>
<br/>

### CapAnalysis
- [CapAnalysis](http://www.capanalysis.net)

[![capanalysis_logo](images/capanalysis_logo.png)](http://www.capanalysis.net)

<div class="container">
<iframe width="420" height="315" src="https://www.youtube.com/embed/kDNFPRoybFQ?rel=0" frameborder="0" allowfullscreen class="video"></iframe>
</div>
<br/>

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/l2QctJwSMcBQ4i" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/ChrisHarrington5/capanalysis-capture-analysis-deep-packet-inspection" title="CapAnalysis - Deep Packet Inspection" target="_blank">CapAnalysis - Deep Packet Inspection</a> </strong> from <strong><a href="//www.slideshare.net/ChrisHarrington5" target="_blank">Chris Harrington</a></strong> </div>
</div>
<br/>
