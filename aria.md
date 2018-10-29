
## ARIA
* ARIA stands for *Accessible Rich Internet Applications*
* WAI-ARIA and ARIA refer to the same thing. However, it is more correct to use WAI-ARIA to acknowledge its origins in WAI (WAI = *Web Accessibility Initiative*)
* `aria` is specifically for accessibility, and should not be used to store random data (`data` is for random data the application needs)

ARIA is a spec defining support for accessible web apps. It defines bunch of markup extensions **(mostly as attributes on HTML5 elements)**, 
which can be used by the web app developer to provide additional information about the semantics of the various elements to assistive technologies like screen readers. 
Of course, for ARIA to work, the HTTP user agent that interprets the markup needs to support ARIA, but the spec is created in such a way, 
as to **allow down-level user agents to ignore the ARIA-specific markup safely without affecting the web app's functionality**.
