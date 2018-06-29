# lua
Some Lua changes of questionable interest and correctness.  Don't blame the Lua team for this.

Branch keni-argcount: Check the number of arguments to Lua-callable functions supplied in the Lua distro.
                      For example: "require('foo', 2)" throws an error because it is documented as "require (modname)"
                      
