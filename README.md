# Context Aware Music Recommendation System

**Pavan Kalyan Reddy Cherupally**  
pcherup1@asu.edu  

**Spoorthi Uday Karakaraddi**  
sudaykar@asu.edu  

**Tanmai Mukku**  
tmukku@asu.edu  

**Sai Siddharth Vemuri**  
svemur13@asu.edu  

## Abstract

Our "Context-Aware Music Recommendation System" enhances traditional music recommendations by incorporating contextual factors such as user’s emotional state, physical environment, and temporal variables. By leveraging Factorization Machines (FMs) and integrating diverse data sources, we improve the relevance and personalization of music recommendations.


## Setup & Running

Run the following set of commands to start the playlist generator:

```bash
cd searching/advanced
python3 gen_playlist.py
```


## Generating a Playlist

There are 4 types of searches that this playlist generator supports

* **Similarity based** : Enter the URI of the query song
* **Dissimilarity based** : Enter the URI of the query song
* **Field based** : Enter the musical feature field followed by <num, #number> or <id, URI> for the song or value with respect to which the playlist is to be generated
* **Mood based** : Enter the mood cluster name *(for eg : mood0)*

## References

#### Network Embeddings 
LINE (Large-scale Information Network Embedding) algorithm. <br>
Reference : https://github.com/shenweichen/GraphEmbedding <br>
Reference Paper : [LINE](https://arxiv.org/pdf/1503.03578.pdf) <br>




