# Custom `nuclei` templates 

Personal collection of [nuclei templates](https://github.com/projectdiscovery/nuclei-templates)

## Host Header Poisoning

Basic check for Host Header Poisoning vulnerability. This template simply adds an arbitrary domain to `X-Forwarded-Host` and `X-Host` to the request and checks if it is reflected to the body of the response.

