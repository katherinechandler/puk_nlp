# Themes in Anthony Bourdain's *Parts Unknown*

Like many travelers I was saddened by the death of travel personality Anthony Bourdain. I'll miss his always interesting and wonderfully humanistic viewpoint terribly, and in this project I applied NLP and clustering tools to identify overarching themes in his CNN series *Parts Unknown*. 

Using non-negative matrix factorization (NMF) to model themes in the episode transcripts, I identified themes of war/conflict, food (no surprise there), a love of Asia (and Asian food), music/art/literature, and drugs/substance abuse. I also mapped how these themes are represented across the locations Bourdain visited.

This repo contains the raw and processed transcript data for this analysis in the `raw_data` and `processed_text` directory, respectively. The full transcript data set (along with episode meta data) is combined in the `puk_all_episodes.csv` file int he `processed_text` directory.

The `parts_unknown_nlp_topic_clustering.ipynb` notebook is the main walkthrough for this analysis, and additional graphs and exploration can be found in `parts_unknown_nlp_full.ipynb`. 

I also wrote a high-level blog about this analysis on my [website](https://katherinechandler.io/post/bourdain_nlp_clustering/). Enjoy!