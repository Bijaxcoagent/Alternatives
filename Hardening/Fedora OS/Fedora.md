# This works for Fedora "Workstation" and Fedora KDE (as of Fedora 44), Fedora "Atomic" and its Derivates Kinoite, Silverblue, Onyx, ... (as of Fedora 34), Rocky Linux (as of Rocky Linux 10), Bazzite, Bluefin and Aurora (as of their first releases)

you dont have to necessarily do countme=0 as it only shows the repository-owner how many people are on their repository (still for you if you are a hardcore privacy emphasizer)
disabling abrt prevents fedora completely from making core dumps (that can include sensitive data), if you still prefer to keep this though, but hate the auto-report, first do `abrt-auto-reporting` then if it says `enabled` `sudo abrt-cli auto-report off`
You could disable the connectivity check as it technically sends a ping to the fedora servers to see if it actually has a connection (fedora servers could know where you are), though this is more "harmless" telemetry, so disable only if you want to
You could disable geoclue.service since it scans your surrounding network with geolocation databases and can track your physical coordinates (disabling it can also technically save some pc ressources)
