#Go Live Checklist

This checklist should be worked through before the launch of any site.

##Prep
301 redirects for existing website are prepared document has been generated
DNS access is determined and access checked (where applicable)
Domain access is determined and access checked (where applicable)

##Development
Development URLs have been changed to production
JS, CSS and images have been minified
Server has been prepped and tuned for production (image caching, max_execution_time has been set correctly)
The admin panel URL has been changed form default /admin or similar
Admin username has been changed / disabled
non-www to www redirect has been setup (where necessary)
non-SSL to SSL redirect has been setup
Favicon has been added
301 redirects have been implemented
Ensure only necessary fonts, weights and character sets are installed
Any CDN'able assets have been switched to use CDN (Google CDN, etc)
Production URLs have been allowed in Webfont packs (Typekit, etc)
Production URLs / IPs have been allowed in API credentials (Google App Console, etc)
Device icons created and display correctly
404 page exists and informative
Print stylesheet has been implemented

##Analytics
Google Tag Manager has been installed and configured
Google Analytics has been added via Google Tag Manager
Website has been verified in Webmaster Tools in our / client Google Account
Website has been registered in Moz.com

##SEO
Generic / fallback SEO meta title, descriptions and keywords configured
MOZ.com site crawl has been run and issue highlighted have been remedied
XML sitemap has been generated and added to root of website
robots.txt is generated and added to root of website (any disallow rules have been removed)
Images use appropriate ALT tags
noindex / nofollow tags have been removed
Open Graph tags included across website and appropriate? (including images where possible)
Schema.org tags have been identified and included across website and appropriate? (including images where possible)
Google My Business property has been registered in client's Google Account

##Testing
301 redirects have been tested
Integrity link checker has been run on the website in-situ
Google PageSpeed has been run and tested
Functions correctly in IE9 using Browserstack
Displays & functions correctly in IE10 using Browserstack
Displays & functions correctly in IE11 using Browserstack
Displays & functions correctly in Firefox (Windows) using Browserstack
Displays & functions correctly in Firefox (Mac) using Browserstack
Displays & functions correctly in Chrome (Windows) using Browserstack
Displays & functions correctly in Chrome (Mac) using Browserstack
Displays & functions correctly in Safari (Mac) using Browserstack
Displays & functions correctly in Safari (iOS – Mobile) using Browserstack
Displays & functions correctly in Safari (iOS – iPad) using Browserstack
Displays & functions correctly in Chrome (iOS – Mobile) using Browserstack
Displays & functions correctly in Chrome (iOS – iPad) using Browserstack
Displays & functions correctly in Chrome (Android – Mobile) using Browserstack
Displays & functions correctly in Chrome (Android – Tablet) using Browserstack
Displays & functions correctly in stock browser (Android) using Browserstack
Displays & functions correctly in Microsoft Edge using Browserstack
Displays & functions correctly on large resolutions using Browserstack
Forms have been tested and processed correctly
All Lorem Ipsum has been removed
All authors have been correctly set on content
Mailchimp newsletter signups are corrcetly registering

##Backups / Server Prep
Regular (daily as a minimum) server *backups* of all servers (web / MySQL) has been configured and retention set for at least 30 days
Less-regular (weekly as a minimum) server *images*
Virtualhost setup on server
SSL certificate has been registered on the server
Remote SSH access as 'root' has been disabled (permissions should be elevated)
Server timezone has been correctly configured according to destination locale

##Deployment
Site has been setup in DeployHQ
Config files (wp-config.php / env.php) have been configured in the Config Files within DeployHQ
Deployment complete with no failures
Form final recipients have been configured and emails have been recieved (SPF / DKIM records have been configured where required)
Submit sitemap to Google Webmaster Tools
Generate a new sitemap.xml and upload to root
Check Analytics data and ensure visits are recorded (pageviews and conversions)