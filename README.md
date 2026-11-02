# pc-watch

Outside heartbeat watchdog for a home PC. The PC writes a timestamp to a private gist every 5 minutes;
this scheduled workflow checks its age and sends a push via ntfy.sh when it goes stale.
No secrets are stored in this repository (gist id and topic are Actions secrets).
