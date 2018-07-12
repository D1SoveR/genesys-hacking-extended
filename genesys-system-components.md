## Hacking System Components

For the purposes of the following components, the *strength* of a given program can be estimated by the kind of system the component being used was designed to protect;

Megacorp core system, intelligence agency server : 5 success
Hacker darknet, military server : 4 success
Government network, corporate server : 3 success
Small business server : 2 success
Public terminal, PAD, personal computer : 1 success

As such, the strength of the individual component, much like in real life, is left to the implementer to decide. This also gives the option to have different networks have particular _flair_ ; a sense of creativity to them, that they have been crafted by the responsible sysadmin.

#####Security Programs

######Authentication Prompt

If a user has the right credentials (or can override the system to make it think they do), they let the user pass. If the user does not, the program automatically boots them from the system.

**Program Strength**: *

**Effects**: If a character attempts to override this program and fails, they immediately lose access to the system they are currently inside, and must perform the Access System action again. Additionally, these can be used to notify Sysops of an intrusion to their network.

######Firewall

Firewalls are effectively barriers in cyberspace that limit access to certain parts of a server or system. If a user tries to penetrate them and fails, they get bumped back to the main system.

**Program Strength**: *

**Effects**: If a character attempts to override this program and fails, they are unable to access the portion of the server the firewall protects (there are no further effects).

######Intrusion Detection Software

IDS don’t stop you from accessing restricted parts of a server. However, they do spot unauthorized access and attempt to trace the offender.

**Program Strength**: *

**Effects**: If a character attempts to override this program and fails, the sysops or other system administrators are immediately notified of the intrusion. In addition, the sentry provides any sysops or system administrators who access the system during the encounter one successful trace against the hacker.
