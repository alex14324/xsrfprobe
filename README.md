

### About [XSRFProbe](https://github.com/0xinfection/xsrfprobe/wiki/)
__XSRFProbe__ is an advanced [Cross Site Request Forgery](https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)) (CSRF/XSRF) Audit and Exploitation Toolkit. Equipped with a Powerful Crawling Engine and Numerous Systematic Checks, it is now able to detect most cases of CSRF vulnerabilities, their related bypasses and futher generate (maliciously) exploitable proof of concepts with each found vulnerability. For more info on how XSRFProbe works, see [XSRFProbe Internals](https://github.com/0xInfection/XSRFProbe/wiki#xsrfprobe-internals) on [wiki](https://github.com/0xInfection/XSRFProbe/wiki/). 

<img src="https://i.imgur.com/xTrfWSt.gif" alt="xsrf-logo">
<p align="center">
  <a href="https://github.com/0xinfection/xsrfprobe/wiki">XSRFProbe Wiki</a> •
  <a href="https://github.com/0xinfection/xsrfprobe/wiki/Getting-Started">Getting Started</a> •
  <a href="https://github.com/0xinfection/xsrfprobe/wiki/General-Usage">General Usage</a> •
  <a href="https://github.com/0xinfection/xsrfprobe/wiki/Advanced-Usage">Advanced Usage</a> •
  <a href="https://github.com/0xinfection/xsrfprobe/wiki/XSRFProbe-Internals">XSRFProbe Internals</a> •
  <a href="https://github.com/0xinfection/xsrfprobe#gallery">Gallery</a>
</p>

### Some Features:

- [x] Performs [several types of checks](https://github.com/0xInfection/XSRFProbe/wiki/XSRFProbe-Internals#types-of-checks) before declaring an endpoint as vulnerable.
- [x] Can detect several types of Anti-CSRF tokens in POST requests.
- [x] Features a powerful crawler which features continuous crawling and scanning.
- [x] Out of the box support for custom cookie values and generic headers.
- [x] Accurate [Token-Strength Detection](https://github.com/0xInfection/XSRFProbe/wiki/XSRFProbe-Internals#token-randomness-calculation) and [Analysis](https://github.com/0xInfection/XSRFProbe/wiki/XSRFProbe-Internals#post-scan-token-analysis) using various algorithms.
- [x] Can generate both normal as well as maliciously exploitable CSRF PoCs.
- [x] Follows a redirect when there is a 30x response.
- [x] Well [documented code](https://github.com/0xInfection/XSRFProbe/tree/master?files=1) and [highly generalised automated workflow](https://github.com/0xInfection/XSRFProbe/wiki#xsrfprobe-internals).
- [x] The user is in [control of everything](https://github.com/0xInfection/XSRFProbe/wiki/Advanced-Usage#xsrfprobe-configuration-variables) whatever the scanner does.
- [x] Has a user-friendly interaction environment with full verbose support.
- [x] Detailed logging system of errors, vulnerabilities, tokens and other stuffs.

### Gallery:
Lets see some real-world scenarios of XSRFProbe in action:

<img src="https://i.imgur.com/AAE1HrE.gif" width=50% /><img src="https://i.imgur.com/TJt103P.gif" width=50% />
<img src="https://i.imgur.com/yzyvXHX.gif" />
<img src="https://i.imgur.com/MhTucgI.gif" width=50% /><img src="https://i.imgur.com/gcfZ9zQ.gif" width=50% />

### Version and License:
XSRFProbe v2.0 release is now a stable release and the work is licensed under the [GPL v3 License](https://www.gnu.org/licenses/gpl-3.0.en.html).

### Warnings:

Do not use this tool on a live site!

It is because this tool is designed to perform all kinds of form submissions automatically which can sabotage the site. Sometimes you may screw up the database and most probably perform a DoS on the site as well.

Test on a disposable/dummy setup/site!

### Disclaimer:
Usage of XSRFProbe for testing websites without prior mutual consistency can be considered as an illegal activity. It is the final user's responsibility to obey all applicable local, state and federal laws. The author assumes no liability and is not exclusively responsible for any misuse or damage caused by this program.

### Author's Words:
This project is based __entirely upon my own research and my own experience with web applications__ on Cross-Site Request Forgery attacks. You can try going through the source code which is highly documented to help you understand how this toolkit was built. Useful [pull requests](https://github.com/0xInfection/XSRFProbe/wiki/Contributing), [ideas and issues](https://github.com/0xInfection/XSRFProbe/wiki/Reporting-Bugs#before-submitting) are highly welcome. If you wish to see what how XSRFProbe is being developed, check out the [Development Board](https://github.com/0xInfection/XSRFProbe/projects/1).

