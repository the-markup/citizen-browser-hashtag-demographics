# Citizen Browser - Hashtags on Facebook
This repository contains code to reproduce the findings featured in our newsletter story, "[The Hashtags of Facebook](https://www.getrevue.co/profile/citizenbrowser/issues/the-hashtags-of-facebook-311304)" from our series, [Citizen Browser](https://themarkup.org/citizen-browser/).

Our methodology is described in "[How We Built a Facebook Inspector](https://themarkup.org/citizen-browser/2021/01/05/how-we-built-a-facebook-inspector)".

## Data
`data/` contains one CSV file showing the top 500 hashtags ranked by number of user accounts they were shown to (`Top-hashtags_2021-02-01.csv`), and four separate CSV files with the demographic data behind each chart that appears in the article.

For the four hashtag CSVs – `berniesmittens.csv`, `blm.csv`,  `covid19.csv`, `maga.csv` – the table columns are as follows:

| column           | decription                                                                                 |
|:-----------------|:-------------------------------------------------------------------------------------------|
| [characteristic] | Name of demographic characteristic represented, e.g. 'race' or 'vote_2020'                 |
| count_hashtag    | The number of user accounts in a demographic group exposed to a hashtag |
| count_all        | Total number of panelists from this demographic in the Citizen Browser cohort        |
| percent          | Panelists exposed as percentage of total panelists in the demographic                      |


## Licensing
Copyright 2021, The Markup News Inc.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
