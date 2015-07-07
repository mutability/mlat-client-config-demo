mlat-client-config-demo
=======================

This is a little example Debian package that provides a
customized mlat-client config that has a separate init
script and generally will run in parallel with any other
mlat-client instances.

To use it:

 * search and replace mlat-client-config-demo to your new
   package name
 * rename debian/mlat-client-config-demo.* so they use the
   new package name
 * customize debian/packagename.templates with whatever
   defaults you want
 * customize debian/packagename.config (near the end) so
   that only the questions you want to prompt for are
   asked.
 * update debian/control and debian/changelog with your info
