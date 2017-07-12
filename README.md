# Single Sign On (SSO)

## Changes : 
<ol>
<li>Update packages</li>
<li>Edit the config to use IIS EXpress</li>
</ol>

# Wiki ~ SSO
Single sign-on (SSO) is a property of access control of multiple related, yet independent, software systems. With this property, a user logs in with a single ID and password to gain access to a connected system or systems without using different usernames or passwords, or in some configurations seamlessly sign on at each system. This is typically accomplished using the Lightweight Directory Access Protocol (LDAP) and stored LDAP databases on (directory) servers.[1] A simple version of single sign-on can be achieved over IP networks using cookies but only if the sites share a common DNS parent domain.[2]

For clarity, it is best to refer to systems requiring authentication for each application but using the same credentials from a directory server as Directory Server Authentication and systems where a single authentication provides access to multiple applications by passing the authentication token seamlessly to configured applications as Single Sign-On.

Conversely, single sign-off is the property whereby a single action of signing out terminates access to multiple software systems.

As different applications and resources support different authentication mechanisms, single sign-on must internally store the credentials used for initial authentication and translate them to the credentials required for the different mechanisms.

Other shared authentication schemes include OAuth, OpenID, OpenID Connect and Facebook Connect. However, these authentication schemes require the user to enter their login credentials each time they access a different site or application so they are not to be confused with SSO.

To be precise, OAuth is not strictly an authentication scheme but an authorization protocol: it provides a way for the users to grant access on their own behalf to other websites or applications using some access keys. The main purpose of the protocol is to exchange the access credentials required for the authentication and not the authentication itself.


# Links:
<a href="https://msdn.microsoft.com/en-us/library/eb0zx8fc.aspx">Forms Authentication Across Applications</a>
