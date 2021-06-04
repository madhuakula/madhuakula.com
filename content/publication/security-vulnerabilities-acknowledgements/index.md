---
title: "Security Vulnerabilities Acknowledgements"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2017-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# publication_types: ["1"]

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

# abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# Summary. An optional shortened abstract.
summary: Details of my security vulnerabilities acknowledgements.

tags: ["Security", "Bug Bounty", "Vulnerabilities", "Acknowledgements"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

| Organization            | Vulnerability       |
|-------------------------|---------------------|
| Google                  | BASM, XSS, DT       |
| Microsoft               | XSS, UE             |
| Yahoo                   | XSS, PM             |
| Barracuda Labs          | XSS, CSRF           |
| Adobe                   | BASM, XSS           |
| At & t                  | CSRF                |
| Blackberry              | CSRF, PD            |
| Magix AG                | XSS                 |
| Scanii                  | CSRF                |
| Linkedin                | LB                  |
| Twitch                  | XSS                 |
| Twilio                  | XSS, BASM           |
| Tumblr                  | XSS, CSRF           |
| Smart Budget            | CSRF                |
| Risk IO                 | XSS                 |
| Get Pocket              | IDOR                |
| Pager Duty              | XSS                 |
| Olark                   | CSRF                |
| Nitrous.io              | XSS                 |
| Mail Chimp              | XSS, IDOR           |
| Magento                 | XSS, CSRF, IDOR, PE |
| Logentires              | XSS                 |
| Librato                 | XSS                 |
| Cisco                   | CSRF                |
| Heroku                  | CSRF, IDOR          |
| Pusher                  | UE                  |
| Form Assembly           | XSS                 |
| Eventbrite              | FU                  |
| Dropmyemail             | XSS                 |
| Dropcam                 | IDOR, XSS, FU       |
| Constant Contact        | XSS                 |
| Blinksale               | CSRF                |
| Bitcasa                 | BASM                |
| Apptentive              | LB                  |
| 123contactform          | XSS, FU             |
| Appcelerator            | AI                  |
| Skmaster                | IDOR                |
| Freshbooks              | CSRF, XSS, TB       |
| LocalBitcoins           | XSS                 |
| Muut                    | XSS                 |
| CloudApp                | XSS                 |
| CloudFlare              | CSRF, AI            |
| Docker                  | LB                  |
| Stopthehacker           | XSS                 |
| Concrete5               | IDOR                |
| ebay                    | XSS, BASM           |
| Coindoe                 | XSS                 |
| KeenIO                  | TB, CSRF            |
| Distimo                 | LB                  |
| Freshdesk               | CSRF, AI            |
| Honeybadger.io          | IDOR                |
| Vzaar                   | CSRF, XSS           |
| Abacus                  | AI                  |
| Active State & Stackato | BASM                |
| OpenpageCRM             | BASM                |
| Pcloud                  | XSS, BASM           |
| Wepay                   | CSRF                |
| Zendesk                 | XSS                 |
| BufferApp               | IDOR                |
| Compose                 | CSRF, XSS           |
| GreenHouse              | LB                  |
| 500px                   | XSS                 |
| Viadeo                  | BASM                |
| Unitag                  | XSS                 |
| Hackerrank              | XSS                 |
| Sony                    | CSRF                |
| Factor.io               | BASM                |
| Inflectra               | XSS                 |
| Movember                | BASM                |
| WHMCS                   | BASM, XSS, CSRF     |
| Acorns, LLC             | BASM, XSS, IDOR     |
| Socrata                 | BASM, CSRF          |
| Many others             | ...                 |

### Legend

* AI: Authentication Issue
* BASM: Broken Authentication & Session Management
* CSRF: Cross Site Request Forgery
* FU: File Upload Vulnerability
* IDOR: Insecure Direct Object Reference
* LB: Logical Bug
* TB: Token Bypass Vulnerability
* UE: Username Enumeration
* XSS: Cross Site Scripting
* PE: Privilege Escalation
* PD: Path Disclosure
* DT: Directory Traversal
