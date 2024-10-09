---
title: 'Election Eligibility with OpenID: Turning Authentication into Transferable Proof of Eligibility'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Véronique Cortier
  - Alexandre Debant
  - Anselme Goetschmann
  - Lucca Hirschi

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-08-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *33rd USENIX Security Symposium*
publication_short: In *USENIX Security 24*

abstract: 'Eligibility checks are often abstracted away or omitted in voting protocols, leading to situations where the voting server can easily stuff the ballot box. One reason for this is the difficulty of bootstraping the authentication material for voters without relying on trusting the voting server. 

In this paper, we propose a new protocol that solves this problem by building on OpenID, a widely deployed authentication protocol. Instead of using it as a standard authentication means, we turn it into a mechanism that delivers transferable proofs of eligibility. Using zk-SNARK proofs, we show that this can be done without revealing any compromising information, in particular, protecting everlasting privacy. Our approach remains efficient and can easily be integrated into existing protocols, as we have done for the Belenios voting protocol. We provide a full-fledged proof of concept along with benchmarks showing our protocol could be realistically used in large-scale elections.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
#   - Large Language Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Link
  url: https://www.usenix.net/conference/usenixsecurity24/presentation/cortier

url_pdf: 'https://www.usenix.net/system/files/usenixsecurity24-cortier.pdf'
url_code: 'https://gitlab.inria.fr/oideli/oideli-artifact'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
url_slides: 'https://www.usenix.net/system/files/usenixsecurity24_slides-cortier.pdf'
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
