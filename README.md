# awesome-music-group-playlist-recommender-system
AMGPRS repo

Spotify recently came with a new feature called ‘Blend’, which takes in two Spotify accounts, and creates a playlist based on both tastes. However, this feature is really bad, the recommendations are bad. It seems like they just take some songs from one account, and some songs from the other account, and called it a recommended mix.
We want to create a model that does this recommendation for two or more people. Recommending them songs based on their shared interests or similarities.
There is a lot of public data. We already found a lot of big datasets of Spotify playlist data, taste and genre data, similarity data, etc.
Some platforms exist that implement a very naïve approach, where only artist similarities are used. We want to create an actual graph mining framework with lots of different types of connections and weights

## Papers

* [Beyond Next Item Recommendation: Recommending and Evaluating List of Sequences](https://arxiv.org/pdf/2008.13281.pdf)
* [Playlist Prediction via Metric Embedding](https://dl.acm.org/doi/pdf/10.1145/2339530.2339643)
* [How Powerful is Graph Convolution for Recommendation](https://arxiv.org/pdf/2108.07567.pdf)
* [GAME: Learning Graphical and Attentive Multi-view Embeddings for Occasional Group Recommendation](https://dl.acm.org/doi/epdf/10.1145/3397271.3401064)
* [Graph Neural Networks in Recommender Systems: A Survey](https://arxiv.org/pdf/2011.02260.pdf)
* [LightGCN: Simplifying and Powering Graph Convolution Network for Recommendation](https://arxiv.org/pdf/2002.02126.pdf)
* [Group-Aware Long- and Short-Term Graph Representation Learning for Sequential Group Recommendation](https://weizhangltt.github.io/paper/SIGIR20-Wang.pdf)
* [Consistency-Aware Recommendation for User-Generated Item List Continuation](https://arxiv.org/pdf/1912.13031.pdf)
* [Graph Neural Netwrok with Interaction Pattern for Group Recommendation](https://arxiv.org/abs/2109.11345)
* [Double-Scale Self-Supervised Hypergraph Learning for Group Recommendation](https://arxiv.org/pdf/2109.04200.pdf)

## Datasets
* [Melon Playlist Dataset](https://mtg.github.io/melon-playlist-dataset/)
* [Spotify Million Playlist Dataset Challenge](https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge)
* [FMA: A Dataset For Music Analysis](https://github.com/mdeff/fma)
* [Million Song Dataset](http://millionsongdataset.com/)
* [The Last.fm Dataset](http://millionsongdataset.com/lastfm/)

## Recommendation platforms
* [Boil The Frog](http://boilthefrog.playlistmachinery.com/)
