# SecureBookSellingWebsite
The purpose of this project was to create a secure book selling website, in particular:
  - Secure session management, including protection against session fixation 
  - No SQL injections or XSS vulnerabilities
  - Log of activities and protection
  - CSRF protection and prevent UI redressing attacks
  - Secure remember me functionality
  - Secure exceptions handlig and no path traversal vulnerability
We use Caddy as webserver, since it provides simple configuration via Caddyfile and automatic HTTPS handling. (Go Caddy :smiley:)
## Requirements
Caddy, PHP fast-cgi, MySQL Server, MailHog (for macOS)  
We use the latest versions
## Credits
  - Fabio Piras
  - Guillaume Quint
  - Giacomo Volpi
## Credits for the dockerization of the project
  - Giacomo Volpi
