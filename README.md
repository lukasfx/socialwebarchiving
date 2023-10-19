# archiving the social web
Assembling approaches to archiving the social web (platforms, feeds) and working with these archives (research and re-publishing).

This is research towards a toolbox and workflows, in the context of my participation in the Art Doc Archive prototype https://art-doc-archive.net/ and comparing existing techniques both from research projects like https://archivesunleashed.org/arch/, as well as the toolsets coming from the PKM (personal knowledge management) scene (like obsidian and zettlr), and connecting this to the open source development happening around the open social web (bridges, apps and plugins related to the fediverse, matrix, deltachat, bluesky and nostr, etc.).

Two main strands of research can be identified:

The webarchiving route:

Mirror: Re-publishing the website data
Archiving: Scraping with webrecorder, browsertrix, HTTrack, see https://zenodo.org/records/7886843
Publishing: Replaying the webrecorder archives, as in the wayback machine.

The personal knowledge management route:

Archiving: Downloading by the users themselves, via GDPR requests
Publishing:
File-based approaches, e.g. converting the downloaded html files to markdown and publishing as a knowledge base.
Visualization approaches, see https://zenodo.org/records/8143785

## examples

# instagram
Export data as html.
Then various approaches:
Umap, see https://zenodo.org/records/8143785 publish as pix-plot
convert to Markdown (pandoc), Obsidian, publish as cosmoscope

# tumblr
export data (as html)
convert to Markdown (pandoc), convert tags (pandoc), Obsidian, publish as cosmoscope

![dataviz](tumblr%20to%20obsidian.png)
Example of a graph view of tumblr tags and posts (ca. 10K posts)

# wordpress
more options through plugins
