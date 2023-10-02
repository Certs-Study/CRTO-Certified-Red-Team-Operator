# Table of contents

* [👋 Exam Guide and Notes](README.md)
* [Author](https://cli-ck.me/rfs)

## 1⃣ Getting Started

* [Course Introduction](getting-started/course-introduction.md)
* [What is Red Teaming?](getting-started/what-is-red-teaming.md)
* [What is OPSEC?](getting-started/what-is-opsec.md)
* [Primum non nocere?](getting-started/primum-non-nocere.md)
* [Attack Lifecycle](getting-started/attack-lifecycle.md)
* [Engagement Planning](getting-started/engagement-planning.md)
* [Post-Engagement & Reporting](getting-started/post-engagement-and-reporting.md)

## 2⃣ Command & Control

* [Page 1](command-and-control/page-1.md)
* [Red Team Ops Lab](command-and-control/red-team-ops-lab.md)
* [Cobalt Strike](command-and-control/cobalt-strike.md)
* [Starting the Team Server](command-and-control/starting-the-team-server.md)
* [Listener Management](command-and-control/listener-management.md)
* [Generating Payloads](command-and-control/generating-payloads.md)
* [Interacting with Beacon](command-and-control/interacting-with-beacon.md)
* [Pivot Listeners](command-and-control/pivot-listeners.md)
* [Running as a Service](command-and-control/running-as-a-service.md)

## 3⃣ External Reconnaissance

* [Page 2](external-reconnaissance/page-2.md)
* [External Reconnaissance](external-reconnaissance/external-reconnaissance.md)
* [DNS Records](external-reconnaissance/dns-records.md)
* [Google Dorks](external-reconnaissance/google-dorks.md)
* [Social Media](external-reconnaissance/social-media.md)

## 4⃣ Initial Compromise

* [🌴 Initial Compromise](initial-compromise/initial-compromise.md)
* [Password Spraying](initial-compromise/password-spraying.md)
* [Internal Phishing](initial-compromise/internal-phishing.md)
* [Initial Access Payloads](initial-compromise/initial-access-payloads.md)
* [Visual Basic for Applications (VBA) Macros](initial-compromise/visual-basic-for-applications-vba-macros.md)
* [Remote Template Injection](initial-compromise/remote-template-injection.md)
* [HTML Smuggling](initial-compromise/html-smuggling.md)

## 🟢 Host Reconnaissance

* [🌴 Host Reconnaissance](host-reconnaissance/host-reconnaissance.md)
* [Processes](host-reconnaissance/processes.md)
* [Seatbelt](host-reconnaissance/seatbelt.md)
* [Screenshots](host-reconnaissance/screenshots.md)
* [Keylogger](host-reconnaissance/keylogger.md)
* [Clipboard](host-reconnaissance/clipboard.md)
* [User Sessions](host-reconnaissance/user-sessions.md)

## 🟢 Host Persistence

* [Host Persistence](host-persistence/host-persistence.md)
* [Startup Folder](host-persistence/startup-folder.md)
* [Registry AutoRun](host-persistence/registry-autorun.md)
* [Hunting for COM Hijacks](host-persistence/hunting-for-com-hijacks.md)
* [Headless Cobalt Strike](host-persistence/headless-cobalt-strike.md)

## 💚 Host Privilege Escalation

* [Host Privilege Escalation](host-privilege-escalation/host-privilege-escalation.md)
* [Windows Services](host-privilege-escalation/windows-services.md)
* [Unquoted Service Paths](host-privilege-escalation/unquoted-service-paths.md)
* [Weak Service Permissions](host-privilege-escalation/weak-service-permissions.md)
* [Weak Service Binary Permissions](host-privilege-escalation/weak-service-binary-permissions.md)
* [UAC Bypasses](host-privilege-escalation/uac-bypasses.md)

## 🟢 Host Persistence (Reprised)

* [Elevated Host Persistence](host-persistence-reprised/elevated-host-persistence.md)
* [Windows Services](host-persistence-reprised/windows-services.md)
* [WMI Event Subscriptions](host-persistence-reprised/wmi-event-subscriptions.md)

## 🟢 Credential Theft

* [Obtaining Credential Material](credential-theft/obtaining-credential-material.md)
* [Beacon + Mimikatz](credential-theft/beacon-+-mimikatz.md)
* [NTLM Hashes](credential-theft/ntlm-hashes.md)
* [Kerberos Encryption Keys](credential-theft/kerberos-encryption-keys.md)
* [Security Account Manager](credential-theft/security-account-manager.md)
* [Domain Cached Credentials](credential-theft/domain-cached-credentials.md)
* [Extracting Kerberos Tickets](credential-theft/extracting-kerberos-tickets.md)
* [DCSync](credential-theft/dcsync.md)

## 🟢 Password Cracking Tips & Tricks

* [Password Cracking Tips & Tricks](password-cracking-tips-and-tricks/password-cracking-tips-and-tricks.md)
* [Wordlists](password-cracking-tips-and-tricks/wordlists.md)
* [Wordlist + Rules](password-cracking-tips-and-tricks/wordlist-+-rules.md)
* [Masks](password-cracking-tips-and-tricks/masks.md)
* [Mask Length & Mask Files](password-cracking-tips-and-tricks/mask-length-and-mask-files.md)
* [Combinator](password-cracking-tips-and-tricks/combinator.md)
* [Hybrid](password-cracking-tips-and-tricks/hybrid.md)
* [kwprocessor](password-cracking-tips-and-tricks/kwprocessor.md)

## 🟢 Domain Reconnaissance

* [Domain Recon](domain-reconnaissance/domain-recon.md)
* [PowerView](domain-reconnaissance/powerview.md)
* [SharpView](domain-reconnaissance/sharpview.md)
* [ADSearch](domain-reconnaissance/adsearch.md)

## 🟢 User Impersonation

* [User Impersonation](user-impersonation/user-impersonation.md)
* [Pass the Hash](user-impersonation/pass-the-hash.md)
* [Pass the Ticket](user-impersonation/pass-the-ticket.md)
* [Overpass the Hash](user-impersonation/overpass-the-hash.md)
* [Token Impersonation](user-impersonation/token-impersonation.md)
* [Process Injection](user-impersonation/process-injection.md)

## 🟢 Lateral Movement

* [Lateral Movement](lateral-movement/lateral-movement.md)
* [Windows Remote Management](lateral-movement/windows-remote-management.md)
* [PsExec](lateral-movement/psexec.md)
* [Windows Management Instrumentation (WMI)](lateral-movement/windows-management-instrumentation-wmi.md)
* [The Curious Case of CoInitializeSecurity](lateral-movement/the-curious-case-of-coinitializesecurity.md)
* [DCOM](lateral-movement/dcom.md)

## 🟢 Session Passing

* [Session Passing](session-passing/session-passing.md)
* [Beacon Passing](session-passing/beacon-passing.md)
* [Foreign Listener](session-passing/foreign-listener.md)
* [Spawn & Inject](session-passing/spawn-and-inject.md)

## 🟢 Pivoting

* [SOCKS Proxies](pivoting/socks-proxies.md)
* [Linux Tools](pivoting/linux-tools.md)
* [Windows Tools](pivoting/windows-tools.md)
* [Browsers](pivoting/browsers.md)
* [Reverse Port Forwards](pivoting/reverse-port-forwards.md)
* [NTLM Relaying](pivoting/ntlm-relaying.md)
