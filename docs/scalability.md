**Table of Contents**
<!-- MarkdownTOC -->

- [Scalability](#scalability)
	- [Scalability and Reliability. Distributed Systems](#scalability-and-reliability-distributed-systems)
	- [Scalability Solutions](#scalability-solutions)

<!-- /MarkdownTOC -->

[![Bicycle parking at Delft Central Station](images/logo-bicycle-dutch.jpg)](https://bicycledutch.wordpress.com/2015/06/02/bicycle-parking-at-delft-central-station/)

<blockquote class="twitter-tweet tw-align-center" data-lang="es"><p lang="en" dir="ltr">This transforming bike is perfect for active parents<a href="https://t.co/fZHudUfuaK">https://t.co/fZHudUfuaK</a></p>&mdash; INSIDER (@thisisinsider) <a href="https://twitter.com/thisisinsider/status/707261266931265536">8 de marzo de 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet tw-align-center" data-lang="es"><p lang="en" dir="ltr">Website performance issues stop UK public from registering to vote <a href="https://t.co/8MjvmxEV7i">https://t.co/8MjvmxEV7i</a> <a href="https://t.co/qAvZfE2HQy">pic.twitter.com/qAvZfE2HQy</a></p>&mdash; TEST Magazine (@testmagazine) <a href="https://twitter.com/testmagazine/status/740482255576047616">8 de junio de 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

# Scalability
- [highscalability.com 🌟🌟](http://highscalability.com/)
	- [highscalability.com: Building nginx and Tarantool based services 🌟](http://highscalability.com/blog/2016/2/17/building-nginx-and-tarantool-based-services.html)
- [All Things Distributed. Werner Vogels' weblog on building scalable and robust distributed systems](http://www.allthingsdistributed.com/)
- [iheavy.com Scalable Startups](http://www.iheavy.com/) MySQL, AWS & Scalability Expert NYC

[![dzone_refcard_ha_scalability](images/dzone_refcard_ha_scalability.png)](https://dzone.com/refcardz/scalability)

[![If you think it's expensive to hire a professional](images/If-you-think-its-expensive-to-hire-a-professional.jpg)](http://www.javiergarzas.com/2014/12/como-y-quien-recupero-healthcare-gov.html)

<blockquote class="twitter-tweet tw-align-center" data-lang="es"><p lang="en" dir="ltr">The Image Optimization Technology that Serves Millions of Requests Per Day <a href="https://t.co/1Gn8xJu9pG">https://t.co/1Gn8xJu9pG</a></p>&mdash; highscalability (@highscal) <a href="https://twitter.com/highscal/status/743112166392369152">15 de junio de 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## Scalability and Reliability. Distributed Systems
- [Scalable Internet Architectures" slides - Theo Schlossnagle how to build scalable production Internet services and... how not to build them](http://lethargy.org/~jesus/misc/Scalable%20Ti.pdf)
	- ["Scalable Internet Architectures" book - Theo Schlossnagle](http://scalableinternetarchitectures.com/)
	- [video: Scalable Internet Architectures - Theo Schlossnagle](https://www.youtube.com/watch?v=2WuT2rdLK5A)
	- [Theo Schlossnagle's slides](http://es.slideshare.net/postwait)
	- Switch configurations should be in version control
	- Router configurations should be in version control
	- Firewall configurations should be in version control
	- System configurations should be in version control
	- Application configurations should be in version control
	- Monitoring configurations should be in version control
	- Documentation should be in version control
	- Application code should be in version control
	- Database schema should be in version control
	- Everything you do should be in version control
	- [5 reasons system administrators should use revision control](https://opensource.com/life/16/7/systems-administrators-should-use-revision-control)
- [slides: Scalable Web Architectures: Common Patterns and Approaches](http://es.slideshare.net/techdude/scalable-web-architectures-common-patterns-and-approaches)
- [video: Making Architecture Matter - Martin Fowler Keynote](https://www.youtube.com/watch?v=DngAZyWMGR0)
- [book: Building Scalable Web Sites - Cal Henderson](http://shop.oreilly.com/product/9780596102357.do)
- [book: Site Reliability Engineering. How Google Runs Production Systems - 2016](http://shop.oreilly.com/product/0636920041528.do)
- [How Does The Use Of Docker effect latency on Linux?](http://highscalability.com/blog/2015/12/16/how-does-the-use-of-docker-effect-latency.html)
- [Cloud Computing: What are the key characteristics of a robust, scalable and healthy cloud architecture?](https://www.quora.com/Cloud-Computing/What-are-the-key-characteristics-of-a-robust-scalable-and-healthy-cloud-architecture) The biggest benefit of moving to the cloud is unsurprisingly a financial one. The financial model associated with the cloud is healthy and economical.
- [dzone: Distributed Systems in the Real World](https://dzone.com/articles/reasoning-about-distributed-systems-in-the-real-wo)

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/2WuT2rdLK5A" frameborder="0" allowfullscreen class="video"></iframe>
</div>
<br>

<div class="container">
<iframe src="//es.slideshare.net/slideshow/embed_code/key/LnRFhtfXLoOMHx" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//es.slideshare.net/postwait/scalable-internet-architecture" title="Scalable Internet Architecture" target="_blank">Scalable Internet Architecture</a> </strong> from <strong><a href="//es.slideshare.net/postwait" target="_blank">Theo Schlossnagle</a></strong> </div>
</div>
<br/>

<div class="container">
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/DngAZyWMGR0?rel=0" frameborder="0" allowfullscreen class="video"></iframe>
</div>
<br/>

<!-- 
<div class="container">
<iframe src="//es.slideshare.net/slideshow/embed_code/key/HghUgbjBasxURW" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//es.slideshare.net/techdude/scalable-web-architectures-common-patterns-and-approaches" title="Scalable Web Architectures: Common Patterns and Approaches" target="_blank">Scalable Web Architectures: Common Patterns and Approaches</a> </strong> from <strong><a href="//es.slideshare.net/techdude" target="_blank">Tech Dude</a></strong> </div>
</div>
<br/> -->

<div class="container">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/gu08awxxcWdiRh" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen class="video"> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/iamcal/scalable-web-architectures-common-patterns-and-approaches-web-20-expo-nyc-presentation" title="Scalable Web Architectures: Common Patterns and Approaches - Web 2.0 Expo NYC" target="_blank">Scalable Web Architectures: Common Patterns and Approaches - Web 2.0 Expo NYC</a> </strong> de <strong><a target="_blank" href="//www.slideshare.net/iamcal">Cal Henderson</a></strong> </div>
</div>
<br/>

## Scalability Solutions
- [OpenShift Dedicated](https://www.openshift.com/dedicated/)
- [OpenStack](http://www.openstack.org/)
- [Apache Mesos](http://mesos.apache.org/)
- [Kubernetes.io](http://kubernetes.io/)
	- [Kubernetes repo analyzed with gitm. Top changeset contributors by employer](https://github.com/karlkfi/kubernetes-gitdm/wiki#top-changeset-contributors-by-employer)
- [Univa Grid Engine](http://www.univa.com/)
- [Apache ZooKeeper](http://zookeeper.apache.org/)
	- [Coordination and service discovery with Apache Zookeeper](http://www.javacodegeeks.com/2013/11/coordination-and-service-discovery-with-apache-zookeeper.html)

<center>
<div class="tumblr-post" data-href="https://embed.tumblr.com/embed/post/iFjXucMPOIj7OILspk20NQ/138981849249" data-did="1ab47fa60263c102949192d73be216fe3f4e0dcd"><a href="http://devopsreactions.tumblr.com/post/138981849249/the-technical-account-manager-when-youre">http://devopsreactions.tumblr.com/post/138981849249/the-technical-account-manager-when-youre</a></div><script async src="https://secure.assets.tumblr.com/post.js"></script>
</center>

[![get healthier](images/Get_Healthier.png)](https://www.quora.com/Cloud-Computing/What-are-the-key-characteristics-of-a-robust-scalable-and-healthy-cloud-architecture)
