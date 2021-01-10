# mod_pony

mod_pony is a joke. It is also an example Apache httpd module, which displays, randomly, either a pony, or the message "not yours" and a picture of a sad little girl who has no pony.

The pony joke is an old one, and a part of the Apache httpd culture.

The joke basically goes like:

"I want x and y and z".
"Also, I want a pony."

The joke being, you're not getting a pony, either.

Ha, ha.

## Installation

Install the module using `apxs`:

`apxs -cia mod_pony.c`

This requires that you have Apache httpd installed, and also that you have `apxs` installed, which probably comes with your distribution's `httpd-devel` (or similarly named) package.
