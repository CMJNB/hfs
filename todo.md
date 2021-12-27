# To do
- anti-csrf
- file sorting
- folders before?
- upload
- log file
- node.comment
- streamable zip archives (no compression, resumable?)
- config: max speed (total/per-ip)
- config: max connections (total/per-ip)
- user.ignoreLimits
- user.redirect
- config: bans
- config: min disk space
- frontend: don't depend on cdn
- webdav?
- vfs: ability to remove/hide/rename files deep in a source
- administration interface
- login without passing clear text password?
  we could use asymmetric encryption, possibly on a hashed password, that means
  we should store a hash2(hash1(password+salt1)), where hash1 is applied on both client
  and server, which grants that even if the encryption is broken only the salt-hashed
  is revealed, which compromises only this server and not others.   
  http://qnimate.com/asymmetric-encryption-using-web-cryptography-api/