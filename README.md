# ocsp with nonce support

This is a modified version of the golang.org/x/crypto/ocsp package.

This version supports the sending/receiving of nonce extensions in the ParseRequest, ParseResponse, CreateRequest, and CreateResponse. 
Both clients and servers can handle nonce extensions.
