# **The Q-LINE MODULE:** 

**Overview:** Provides the /QLINE and /UNQLINE commands, allowing O-lined users with the server-ban:gline privs to manually add Q-lines (global nick bans) 
at the network level, rather than relying on Services to do so via the /(UN)SQLINE server-only command or config file access.

## **USAGE:**
 
Add a new Q-line entry: `/QLINE <nickmask> :<Reason>`

Delete an active Q-line entry: `/UNQLINE <nickmask>`

View list of Q-lines: `/STATS q`

---

## **Instructions on Loading:**

Once properly  compiled, as with all other third-party modules, you must include the module within your server's `unrealircd.conf` file. Specifically via the following syntax: 

> `loadmodule "third/qline";`

Then rehash the server with `./unrealircd rehash` or with the corresponding oper command client-side.
---

## **Help:**

For any help, bug reports, questions, or concerns with the module in question, please contact Hexick by any of the following ways:

* **Email:** me@hexick.com
* **The UnrealIRCd Network:** Nick - Hex 
