2021-01-15 - Initial build

- Pre-installed microG (0.2.16.204713-10) and F-Droid like the LineageOS for microG project (own fork)
- Pre-installed AuroraStore
- Bromite as default browser (87.0.4280.106)
- eSpeak TTS engine (FOSS TTS solution)
 Additional security hardening features listed below:
- Cloudflare as default DNS (instead of Google)
- Privacy-preferred default settings
- Optional blocking of Facebook- and Google-Tracking (Settings - Network & Internet)
- Optional disable captive portal detection or choose from various providers (default is GrapheneOS and not Google; Settings - Network & Internet)
- Firewall UI (under Trust)
- Increased max. password length of 64
- No submission of IMSI/phone number to Google when GPS is in use
- Default hosts file with many blocked ad/tracking sites
- Privacy-enhanced Bromite SystemWebView (87.0.4280.131)
- Extra control of sensor access for additionally installed user apps (Special access under app permissions)
- Additional restriction options for secondary users
- Constified JNI method tables and hardened bionic lib


