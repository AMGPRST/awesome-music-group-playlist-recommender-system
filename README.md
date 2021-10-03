# AMGPRS: Awesome Music Group Playlist Recommender System

Spotify recently came with a new feature called ‘Blend’, which takes in two Spotify accounts, and creates a playlist based on both tastes. However, this feature is really bad, the recommendations are bad. It seems like they just take some songs from one account, and some songs from the other account, and called it a recommended mix.
We want to create a model that does this recommendation for two or more people. Recommending them songs based on their shared interests or similarities.
There is a lot of public data. We already found a lot of big datasets of Spotify playlist data, taste and genre data, similarity data, etc.
Some platforms exist that implement a very naïve approach, where only artist similarities are used. We want to create an actual graph mining framework with lots of different types of connections and weights.

## Related works
* [Graph Neural Networks in Recommender Systems: A Survey (2021)](https://arxiv.org/pdf/2011.02260.pdf)

### Recommendation with graphs
* [How Powerful is Graph Convolution for Recommendation (2021)](https://arxiv.org/pdf/2108.07567.pdf)
* [LightGCN: Simplifying and Powering Graph Convolution Network for Recommendation (2020)](https://arxiv.org/pdf/2002.02126.pdf)

### Sequential recommendation
* [Beyond Next Item Recommendation: Recommending and Evaluating List of Sequences (2020)](https://arxiv.org/pdf/2008.13281.pdf)
* [Group-Aware Long- and Short-Term Graph Representation Learning for Sequential Group Recommendation (2020)](https://weizhangltt.github.io/paper/SIGIR20-Wang.pdf)
* [Time Matters: Sequential Recommendation with Complex Temporal Information (2020)](https://dl.acm.org/doi/pdf/10.1145/3397271.3401154)
* [Next-item Recommendation with Sequential Hypergraphs (2020)](https://dl.acm.org/doi/pdf/10.1145/3397271.3401133)
* [Consistency-Aware Recommendation for User-Generated Item List Continuation (2020)](https://arxiv.org/pdf/1912.13031.pdf)

### Group recommendation
* [GAME: Learning Graphical and Attentive Multi-view Embeddings for Occasional Group Recommendation (2020)](https://dl.acm.org/doi/pdf/10.1145/3397271.3401064)
* [Group-Aware Long- and Short-Term Graph Representation Learning for Sequential Group Recommendation (2020)](https://weizhangltt.github.io/paper/SIGIR20-Wang.pdf)
* [Graph Neural Netwrok with Interaction Pattern for Group Recommendation (2021)](https://arxiv.org/pdf/2109.11345.pdf)
* [Double-Scale Self-Supervised Hypergraph Learning for Group Recommendation (2021)](https://arxiv.org/pdf/2109.04200.pdf)

### Music embedding
* [Playlist Prediction via Metric Embedding (2012)](https://dl.acm.org/doi/pdf/10.1145/2339530.2339643)
* [CAME: Content- and Context-Aware Music Embedding for Recommendation (2020)](https://ieeexplore.ieee.org/abstract/document/9067038)
* [Music2Vec: Music Genre Classification and Recommendation System (2020)](https://ieeexplore.ieee.org/abstract/document/9297559)
* [Quick Lists: Enriched Playlist Embeddings for Future Playlist Recommendation (2020)](https://arxiv.org/pdf/2006.12382.pdf)

## Datasets
* [Melon Playlist Dataset](https://mtg.github.io/melon-playlist-dataset/)
* [Spotify Million Playlist Dataset Challenge](https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge)
* [FMA: A Dataset For Music Analysis](https://github.com/mdeff/fma)
* [Million Song Dataset](http://millionsongdataset.com/)
* [The Last.fm Dataset](http://millionsongdataset.com/lastfm/)

## Recommendation platforms
* [Boil The Frog](http://boilthefrog.playlistmachinery.com/)
* [Obscurify Music](https://obscurifymusic.com/home)
