# nginx
conf.d proxy configs

## defaults.conf

Ingests traffic for all subdomains of a given domain.

Redirects all traffic on port 80 to 443 to their respective hosts & URI based on the headers.

Closes the default site from port 80 and port 443.
