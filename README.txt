=== About ===
This CLI tool is designed to provide an easy CLI tool for interacting with the esgob
anycast secondary DNS service API

It does what I need it to, but is supplied with no warranty or expression that it's fit for your purpose.

In short, if it eats your cat, or causes your hamster to blow a gasket, that's not my fault.

=== Configuration ===
You can whack standard config items in any of (and searched in this order) :

/etc/esgob.conf
/usr/local/etc/esgob.conf
~/.esgobrc

Lines are formatted as follows:

account some_account_name
key kskjhdkjdhkjhdkjdhdkjhdkjhd

=== Usage ===
Running esgob without any options will show you the API methods supported. Running with an action,
but missing required parameters will show you the ones required, as per the API docs at:

https://noc.esgob.com/docs/api
