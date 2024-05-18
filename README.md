# Context Aware Music Recommendation System

**Tanmai Mukku**  
tmukku@asu.edu  

**Pavan Kalyan Reddy Cherupally**  
pcherup1@asu.edu  

**Spoorthi Uday Karakaraddi**  
sudaykar@asu.edu  

**Sai Siddharth Vemuri**  
svemur13@asu.edu  

## Abstract

Music recommendation systems play a pivotal role in the digital music industry, significantly enhancing user experience by personalizing music selections. However, the majority of existing systems predominantly focus on leveraging user preferences and song metadata, neglecting the critical influence of contextual information on music choice. Our project, "Context-Aware Music Recommendation System," seeks to bridge this gap by incorporating a variety of contextual factors, such as the user’s emotional state, physical environment, and temporal variables, into the recommendation process.

![Context Aware Music Recommendation System](images/music.png)

## Setup & Running

Run the following set of commands to start the playlist generator:

```bash
cd searching/advanced
python3 gen_playlist.py


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




