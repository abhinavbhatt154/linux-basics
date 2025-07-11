# linux-basics
1//  whatweb-
        WhatWeb identifies websites. It recognises web technologies including content management systems (CMS), blogging platforms, statistic/analytics packages, JavaScript libraries, web servers, and embedded devices.
        WhatWeb has over 900 plugins, each to recognise something different. It also identifies version numbers, email addresses, account IDs, web framework modules, SQL errors, and more.
           Usage: whatweb [options] <URLs>
           to know about whatweb, (  whatweb --help  )
           use case-
              1/ to know in brief,for example
                whatweb w3school.com    //simple
                whatweb -a 3 w3school.com  // with agrresion level
              2/ we can also use for active ip in range
                to find your ip
                  ifconfig ,then
                whatweb 10.0.2.0-10.0.2.255 -v

2//  theharvester-  (not installed mainly)
        The package contains a tool for gathering subdomain names, e-mail addresses, virtual hosts, open ports/ banners, and employee names from different public sources (search engines, pgp key servers).
              usage: restfulHarvest [-h] [-H HOST] [-p PORT] [-l LOG_LEVEL] [-r]
 
3// sherlock-         (not installed mainly)
        Find Usernames Across Social Networks *****
        Sherlock relies on the site’s designers providing a unique URL for a registered username. To determine if a username is available, Sherlock queries that URL, and uses to response to understand if there is a claimed username already there.
      eg- sherlock https://www.w3schools.com/

4// sublist3r -
         This package contains a Python security tool designed to enumerate subdomains of websites using OSINT. It helps penetration testers and bug hunters collect and gather subdomains for the domain they are targeting over the network
      eg-sublist3r -d w3schools.com