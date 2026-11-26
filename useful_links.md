# Main question
**Can AI replace artists?**

## Possible subquestions


## List of the useful links and possible datasets for the assignments

1. [Music and Artificial Intelligence: Artistic Trends](https://github.com/jordipons/ai-music-artistic-trends)

````{verbatim}
[ Project | Artist | Year | Use of AI | Format | Origin of release ]
````
The dataset is taken from the paper [How musicians use AI for music production](https://arxiv.org/html/2508.11694v1).
It covers the period 2017-2025.
The releases included come primarily from the "AI Song Contest" and it describes what is the usage of AI in the production process of the artist.

A possible question linked to the dataset is "What the AI is capable of doing (in music production)?".

2. [Impact of AI on Digital Media (journalism, advertising, social media)](https://www.kaggle.com/datasets/atharvasoundankar/impact-of-ai-on-digital-media-2020-2025)

````{verbatim}
[ Country | Year | Industry | AI adoption rate (%) | AI-Generated content (TBs per year) | Job loss due to AI (%) | Revenue increase due to AI (%) | Human-AI collaboration rate (%) | Top AI tools used | Regulation status | Consumer trust in AI (%) | Market share of AI companies (%) ]
````
The dataset collects data from various sources (MIT, Standford, ArXiv and others) and it describes how the use of AI impacts digital media like social media, video games, marketing and many other fields, covering AI adoption rates, job losses and consumer trust.
It covers the period 2020-2025.

Possible questions linked to the dataset are "How does the public perceive AI products?", "Is AI taking the place of human workers in creative fields?".

3. [Whether and why we prefer human-created compared to AI-created artwork](https://osf.io/cgw8v/overview)

The datasets are taken from the paper [Humans versus AI: whether and why we prefer human-created compared to AI-created artwork](https://pmc.ncbi.nlm.nih.gov/articles/PMC10319694/#Sec4).
It proposes two studies in which participants were asked to rate different artistic values of artworks with random human-generated/AI-generated labels.

Possible questions linked to the dataset are "Are people biased when judging AI-generated artworks?", "Can people discriminate human-generated from AI-generated artworks?".

4. [Interpretation of AI-generated vs. Human-made images](https://www.mdpi.com/article/10.3390/jimaging11070227/s1)

The dataset is taken from the paper [Interpretation of AI-Generated vs. Human-Made Images](https://www.mdpi.com/2313-433X/11/7/227#Article_Metrics) and covers a survey on how the participants perceived the images based on their supposed origin (AI or human), the level of realism and the level of credibility.

Possible questions linked to the dataset are "Is the public able to discriminate between AI-generated and human-made artworks?", "Are AI artworks perceived as credible?".

5. [More surveys on AI perception](https://osf.io/xs8bv/?view_only=96a2b4c29a5b4adf8cca18025e18811c)

The datasets are taken from the paper [Bias against AI art can enhance perceptions of human creativity](https://pmc.ncbi.nlm.nih.gov/articles/PMC10624838/) and it discusses various surveys in which the participants where asked to rate different artistic values of the artworks which were randomly assigned an AI-generated or human-created label. 

Possible questions linked to the dataset are "Is the public biased against AI-generated artworks?", "Do AI artworks have artistic value for the public?".

- AI slop in music streaming: https://arxiv.org/html/2606.18052v1#bib (very big dataset, 200GB of metadata from Spotify tracks, the paper used another tool to estimate which albums were AI generated and which we human generated, data at this [link](https://www.kaggle.com/datasets/lordpatil/spotify-metadata-by-annas-archive))
- Upwork Market Index: https://github.com/snipeworkapp-oss/upwork-market-data
- Generative Artificial Intelligence, Adoption Rate for Work: Arts, Design, Entertainment, Sports, and Media Occupations https://fred.stlouisfed.org/data/RPSGENAIUSAGESHAREOCC9
- How AI is useful for artists' productivity: https://academic.oup.com/pnasnexus/article/3/3/pgae052/7618478#449111171
- How closely does AI-generated music follow what people ask for, and what emotions does it convey, compared with the human-made music it was prompted from? Sources:https://pmc.ncbi.nlm.nih.gov/articles/PMC11332804/  Dataset:https://www.kaggle.com/datasets/2ab339f9bbc64cf1b13beb52b0bef0a3f8401bfe1ed6e583b748a3e08b1a0a28
- [Enterprise GenAI Adoption & Workforce Impact Data](https://www.kaggle.com/datasets/tfisthis/enterprise-genai-adoption-and-workforce-impact-data)
- [Global AI Tool Adoption Across Industries](https://www.kaggle.com/datasets/tfisthis/global-ai-tool-adoption-across-industries/data)
- [AI Impact on Job Sector](https://www.kaggle.com/datasets/sumeakash/ai-impact-on-job-sector)
- [Chat with Gemini](https://share.gemini.google/eiyQhxZBZrRr)
- [Eurostat](https://ec.europa.eu/eurostat/databrowser/view/isoc_eb_ai/default/table?lang=en)
- [Anthropic](https://huggingface.co/datasets/Anthropic/EconomicIndex/tree/main/labor_market_impacts)
- [GenAI exposure scores for ISCO-08 occupations](https://github.com/pgmyrek/2025_GenAI_scores_ISCO08/tree/main)

## Plots for assignment 1

- Barchart: percentage of job losses grouped for industry (dataset: *Impact of AI on Digital Media*)
- Grouped barchart: how do AI adoption varies across different industries grouping by company size (dataset *Global AI Tool Adoption Across Industries*)
- Come varia l'adozione dell'IA tra i diversi settori in base alla dimensione dell'azienda (o all'anno)?
- Heatmap: show productivity change based on education degree and industry (dataset: *AI Impact on Job Sector*)
- 100% stacked barchart: group AI tool percentage per industry (dataset: *Enterprise GenAI Adoption & Workforce Impact Data*)
- Waffle chart: **automation_risk**/job_growth_projection per 100 workers (dataset *AI Impact on Job Sector*)
- Ogni quadratino rappresenta l'1% del campione, colorato in base a Automation_Risk (Low, Medium, High) oppure Job_Growth_Projection (Growth, Stable, Decline).
