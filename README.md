# porkbun-fastmail

CLI to quickly add DNS records for [Fastmail](https://fastmail.com) to a [Porkbun](https://porkbun.com) domain.

### Getting Started
1. Generate API tokens using the Porkbun [docs](https://kb.porkbun.com/article/190-getting-started-with-the-porkbun-api).
2. Enable API access on the domain(s) you want to add records to (the "Installing keys and enabling API access on specific domains" in the previous docs link)
3. Run `python main.py <yourdomain>`
4. Verify the records were created correctly in the Porkbun admin panel
5. Check the DNS records in the [Fastmail domain settings](https://app.fastmail.com/settings/domains)
6. (Optional) Add a new email address in the [Fastmail email addresses settings](https://app.fastmail.com/settings/addresses)
7. (Optional) Send a test email to and from your new email address

### Notes
The Porkbun API docs: https://porkbun.com/api/json/v3/documentation.

The archived [porkbun-dynamic-dns-python](https://github.com/porkbundomains/porkbun-dynamic-dns-python/) project was also used for reference.
