# ClobberProtect
Palo Alto GlobalProtect VPN client stored password retrieval

![alt text](https://github.com/billchaison/ClobberProtect/blob/master/gpcs.png)

The Palo Alto GlobalProtect VPN client for Windows allows a user to store their password, making it easy to reconnect later.  From a pentester's perspective, user credentials are a highly valued target.  This article describes how to decrypt a user's GlobalProtect password from the Windows registry.  The steps assume that you already have access to the user's computer and can obtain the machine SID as well as read the user's registry settings under HKEY_CURRENT_USER.

The ClobberProtect exploit resides under a protected repository in my BitBucket

https://bitbucket.org/billchaison/clobberprotect/
