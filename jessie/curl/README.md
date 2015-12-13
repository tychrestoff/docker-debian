# README.md
### Let's get started: `docker pull tychrestoff/debian:curl`

Debian Jessie with curl, wget, and ca-certificates. Inherits from `tychrestoff/debian:min`.

####Utility details
  * [**`ca-certificates`**](https://packages.debian.org/jessie/ca-certificates)
    * PEM files of CA certificates to allow SSL-based applications to check for authenticity of SSL connections
  * [**`curl`**](https://packages.debian.org/jessie/curl)
    * CLI for transferring data with URL syntax
    * Supports many protocols:
      * HTTP
      * HTTPS
      * SMTP
      * IMAP
      * POP3
      * FTP
      * LDAP
      * etc.
    * API for:
      * SSL certificates
      * HTTP POST, PUT
      * FTP uploading
      * proxies
      * cookies
      * user/password authentication
      * proxy tunneling
  * [**`wget`**](https://packages.debian.org/jessie/wget)
    * Network utility to retrieve files from the web using HTTP, HTTPS, and FTP
    * Works non-interactively even after logging off
