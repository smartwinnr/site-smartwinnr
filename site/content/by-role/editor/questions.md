---
author:
  name: SmartWinnr
  email: smartwinnr@mobillionlabs.com
description: 'This quick answer shows how to create CAA records for domains and subdomains.'
og_description: 'This quick answer will show you how to create a CAA record for domains and subdomains'
keywords: ["questions", "dns", "records", "subdomain", "domain"]
license: '[CC BY-ND 4.0](https://creativecommons.org/licenses/by-nd/4.0)'
modified: 2017-11-03
modified_by:
  name: SmartWinnr
published: 2017-11-03
title: Questions
weight: 40
external_resources:
 - '[CAA Records, DNSimple](https://support.dnsimple.com/articles/caa-record/)'
 - '[RFC 6844: DNS Certification Authority Authorization (CAA) Resource Record](https://tools.ietf.org/html/rfc6844)'
---

Certification Authority Authorization (CAA) is a type of DNS record that allows the owner of a domain to specify which certificate authority (or authorities) are allowed to issue SSL/TLS certificates for their domain(s). This quick answer shows you how to set up CAA records on your Linode.


## Questions

1.  This is an overview of almost every thing SmartWinnr offers.

2.  Select the domain you want to add the record to, or add a domain if you don't already have one listed.

3.  Under the **CAA Records** section, select **Add a new CAA record**.

4.  Here's an explanation of the form fields:

    **Subdomain**: This field indicates the domain or subdomain you want the CAA record to cover. To apply it to your entire website (`example.com`), you can just leave this field blank. To limit the record's application to a subdomain on your site, (`subdomain.example.com`), enter that into the form field.

    **Tag**:

     -  *issue* - Authorize the certificate authority entered in the *Value* field further below to issue TLS certificates for your site.

     -  *issuewild* - Same as above, with the exception that you were issued a wildcard certificate.

     -  *iodef* - URL where your CA can report security policy violations to you concerning certificate issue requests.

    **Value**: If the *issue* or *issuewild* tag was selected above, then the value field takes the domain of your certificate issuer (for example: `letsencrypt.org`). If the *iodef* tag was selected, the value field takes a contact or submission URL (`http` or `mailto`).

    **TTL (Time to Live)**: Time in seconds that your new CAA record will be cached by Linode's DNS name servers before being refreshed. The *Default* selection's TTL is 300 seconds, which is fine for most cases. You can use `dig` to view the remaining time your DNS records will be cached until refreshed. Replace *linode.com* with your site's domain or subdomain in the command below:

        root@debian:~# dig +nocmd +noall +answer example.com
        example.com.     167 IN  A   203.0.113.1

5.  Select **Save Changes** when finished. The CAA record should be fully propagated within the TTL duration.
