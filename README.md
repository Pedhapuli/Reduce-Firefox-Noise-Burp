markdown

# Reduce-Firefox-Noise-Burp

Open about:config in firefox

To stop sending errors, other information to Mozilla, stop the telemetry
1. **datareporting.policy.dataSubmissionEnabled ---> False**
2. datareporting.healthreport.uploadEnabled ---> False
3. toolkit.telemetry.unified ---> False
4. dom.push.enabled
5. dom.push.connection.enabled

Stop Captive Portal Check
6. **network.captive-portal-service.enabled ---> False**

Stop below service by searching and double clicking
7. services.sync.prefs.sync.browser.safebrowsing.malware.enabled
8. browser.safebrowsing.malware.enabled
9. browser.safebrowsing.phishing.enabled
10. browser.safebrowsing.downloads.enabled

To stop auto updates, search for "Update.enabled" and double click all the results
11. app.update.enabled
12. extensions.update.enabled
13. lightweightThemes.update.enabled
14. services.sync.prefs.sync.extensions.update.enabled
15. services.blocklist.update_enabled
