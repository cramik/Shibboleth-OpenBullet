# Shibboleth-OpenBullet

OpenBullet script to check user credentials against a Shibboleth server with Duo forced.

Is setup to use OpenBullet 1.4.4 [Anomaly Modded Version] since it was the only one I could properly get username:password credential lists to work on

Usage:
replace [WEBSITE] with the intended target, copy to OpenBullet config folder, configure in runner, start

I will likely eventually set this up as a python script since it's not massively complicated and OpenBullet is unneccesary.

Additionally, the use of two different subdomains to make requests to means that this script might not be as cross-compatible as it should be, so finding a solution to just derive the url of shibboleth via the portal would be ideal
