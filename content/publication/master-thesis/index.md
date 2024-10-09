---
title: 'Design and Analysis of Graph Encryption Schemes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Anselme Goetschmann
  - Kenny Paterson
  - Sikhar Patranabis


date: '2020-09-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['thesis']

# Publication name and optional abbreviated publication name.
publication: Master Thesis at *ETH Zurich*
publication_short: Master Thesis at *ETH Zurich*

abstract: 'With the advent of cloud storage and computing, the related privacy issues have attracted the attention of researchers. This has resulted in the development of encrypted databases which can be queried without the server learning the content of the database or of the queries. Although provably secure by some definitions, such schemes rely on a trade-off between security and efficiency and thus leak a controlled amount of information to the server. The analysis of the various types of leakages has evolved in parallel to the development of new schemes and has revealed important potential attacks.

In this Master’s thesis, we focus on encrypted databases designed for data in the form of graphs such as social networks or web graphs. Since the leakage resulting from encrypted graph databases has not yet been subject to thorough anaylsis we explore this topic. More specifically, we consider schemes running shortest path queries on graphs and in particular encrypted sketch-based distance oracles like the GRECS scheme introduced by Meng et al. in ACM CCS 2015. To our knowledge, the sketch pattern leakage occuring in this type of construction has not yet
been analysed.

Based on two different algorithms to build distance sketches, we investigate how much information the sketch pattern reveals about the sketches themselves. Using our observations, we explore potential attacks which could be mounted by a malicious server. In particular, we propose a query recovery attack feasible by an attacker with partial database knowledge. Our results show that the sketch pattern leakage can reveal sensitive information to the server and we propose a modification to the sketching algorithm to mitigate the impact of the sketch pattern leakage on privacy.'


# Display this page in the Featured widget?
featured: true


url_pdf: 'https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/444763/2/Goetschmann_Anselme.pdf'
url_code: 'https://github.com/agoetschm/master-thesis'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: 'https://www.usenix.net/system/files/usenixsecurity24_slides-cortier.pdf'
# url_video: 'https://youtube.com'

---