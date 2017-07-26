Plataformas e arquiteturas
==========================

Adotar
------

### OpenNebula

...


Experimentar
------------

### HSTS

HTTP Strict Transport Security (HSTS) is a now widely supported policy that allows websites to protect themselves from downgrade attacks. A downgrade attack in the context of HTTPS is one that can cause users of your site to fall back to HTTP rather than HTTPS, allowing for further attacks such as man-in-the-middle attacks. With HSTS, the server sends a header that informs the browser that it should only use HTTPS to access the website. Browser support is now widespread enough that this easy-to-implement feature should be added to any site using HTTPS. Mozilla’s Observatory can help identify this and other useful headers and configuration options that improve security and privacy. When implementing HSTS, it is critical to verify that all resources load properly over HTTPS, because once HSTS is turned on, there is (almost) no turning back until the expiry time. The directive to include subdomains should be added but, again, a thorough verification that all subdomains support secure transport is required.


Testar
------


Estudar
-------

### Webassembly e asm.js

...


Em suspenso
-----------


Evitar
------

### CMS as platform (wordpress)

We are seeing too many organizations run into trouble as they attempt to use their CMS as a platform for delivering large and complex digital applications. This is often driven by the vendor-fueled hope of bypassing unresponsive IT organizations and enabling the business to drag and drop changes directly to production. While we are very supportive of providing content producers with the right tools and workflows, for applications with complex business logic we tend to recommend treating your CMS as a component of your platform (often in a hybrid or headless mode) cooperating cleanly with other services, rather than attempting to implement all of your functionality in the CMS itself.
