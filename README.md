# Reduce-Firefox-Noise-Burp

Open about:config in firefox

To stop sending errors, other information to Mozilla, stop the telemetry
**datareporting.policy.dataSubmissionEnabled ---> False**
datareporting.healthreport.uploadEnabled ---> False
toolkit.telemetry.unified ---> False
dom.push.enabled
dom.push.connection.enabled
Stop Captive Portal Check
**network.captive-portal-service.enabled ---> False**
Stop below service by searching and double clicking
services.sync.prefs.sync.browser.safebrowsing.malware.enabled
browser.safebrowsing.malware.enabled
browser.safebrowsing.phishing.enabled
browser.safebrowsing.downloads.enabled
To stop auto updates, search for "Update.enabled" and double click all the results
app.update.enabled
extensions.update.enabled
lightweightThemes.update.enabled
services.sync.prefs.sync.extensions.update.enabled
services.blocklist.update_enabled
