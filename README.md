# Reduce-Firefox-Noise-Burp

### Open `about:config` in Firefox

To stop sending errors and other information to Mozilla, disable telemetry by changing the following settings:

1. **`datareporting.policy.dataSubmissionEnabled`** → `False`
2. **`datareporting.healthreport.uploadEnabled`** → `False`
3. **`toolkit.telemetry.unified`** → `False`
4. **`dom.push.enabled`** → `False`
5. **`dom.push.connection.enabled`** → `False`

### Stop Captive Portal Check

6. **`network.captive-portal-service.enabled`** → `False`

### Stop the Following Services by Searching and Double-Clicking:
7. **`services.sync.prefs.sync.browser.safebrowsing.malware.enabled`** → `False`
8. **`browser.safebrowsing.malware.enabled`** → `False`
9. **`browser.safebrowsing.phishing.enabled`** → `False`
10. **`browser.safebrowsing.downloads.enabled`** → `False`

### Disable Auto Updates
To stop auto updates, search for `"Update.enabled"` and double-click all the results:

11. **`app.update.enabled`** → `False`  
12. **`extensions.update.enabled`** → `False`  
13. **`lightweightThemes.update.enabled`** → `False`  
14. **`services.sync.prefs.sync.extensions.update.enabled`** → `False`  
15. **`services.blocklist.update_enabled`** → `False`
