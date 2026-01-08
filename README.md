# Disposable email domains

For more informations, please check the [main repository](https://github.com/disposable/disposable).

To check if a domain is listed on the disposable email list and check the source for the record, please use the [lookup form](https://amankumar171837.github.io/update-disposable-email-domains/lookup).

---

*If your domain is listed and it is not a domain used for temporary emails, please open [an issue](https://github.com/Amankumar171837/update-disposable-email-domains/issues) in the master repository.*

---

### Generic lists with all domains

* [TXT](https://amankumar171837.github.io/update-disposable-email-domains/domains.txt): `https://disposable.github.io/disposable-email-domains/domains.txt`
* [JSON](https://amankumar171837.github.io/update-disposable-email-domains/domains.json): `https://disposable.github.io/disposable-email-domains/domains.json`

### Hosts with validated DNS (a valid MX / A record):

* [TXT](https://amankumar171837.github.io/update-disposable-email-domains/domains_mx.txt): `https://disposable.github.io/disposable-email-domains/domains_mx.txt`
* [JSON](https://amankumar171837.github.io/update-disposable-email-domains/domains_mx.json): `https://disposable.github.io/disposable-email-domains/domains_mx.json`

### List of SHA1

* [TXT](https://amankumar171837.github.io/update-disposable-email-domains/domains_sha1.txt): `https://disposable.github.io/disposable-email-domains/domains_sha1.txt`
* [JSON](https://amankumar171837.github.io/update-disposable-email-domains/domains_sha1.json): `https://disposable.github.io/disposable-email-domains/domains_sha1.json`



**Overview**

*This repository is a fork of the original project with a simplified and optimized approach. The scraping logic has been completely removed to reduce complexity and improve reliability. Instead, an additional external source—already responsible for maintaining and updating disposable email domain data—has been integrated into the GitHub Actions workflow.*

> By relying on a pre-scraped and actively maintained source, the workflow runs faster and more efficiently. The final output is a plain text (.txt) file containing disposable email domains, which can be easily consumed and stored by downstream services or applications.


**Key Changes**

* Removed in-repository scraping logic

* Integrated an external, pre-maintained source for domain data

* Faster and more reliable GitHub Actions workflow

* Simple .txt output for easy usage and storage
