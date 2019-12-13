# Fake news in social media. Network perspective
IMI project studying fake news in Switzerland.

In this project, we focus on the networks to understand how fake news are spreaded. We study user networks and filter bubbles (the effect when users are trapped in an information bubble which prevents them from being exposed to alternative opinions). Click on the links to explore the network view.

## 1. Twitter
Here, we extract networks of Twitter accounts spreading information about controvercial topics. 

* [General controvercial topics](https://mizvol.github.io/imi-nets/network/)
* [Conspiracy](https://mizvol.github.io/imi-nets/network-twitter-conspiracy)

## 2. Youtube*
Here, we study various youtube networks. We have two lists of videos. One contains videos about controvercial topics. We call them sources of information. The other has videos that were identified as fake by an expert. 

First, we extract networks of videos, users, and channels. Two videos are connected if YouTube recommends watching one video after another. Two channels are connected if they feature each other or share a video. Two users are connected if they interact in the comment section.

### 2.1 Sources of information

#### 2.1.2 Climate change
* [Video recommendation network](https://mizvol.github.io/imi-nets/youtube/youtube-diffuseurs-climate/)
* [Featured channels network](https://mizvol.github.io/imi-nets/youtube/youtube-channels-diffuseurs-climate/)

### 2.2 Potential fake news channels

#### 2.2.2 Climate change. Fake news
* [Video recommendation network](https://mizvol.github.io/imi-nets/youtube/youtube-videos-climate-fake/)
* [Featured channels network](https://mizvol.github.io/imi-nets/youtube/youtube-channels-climate-fake/)
* [Users comment network](https://mizvol.github.io/imi-nets/youtube/youtube-users-comments-climate-fake/)

#### 2.2.1 Chemtrails. Fake news
These videos are not very popular, so very few users comment on them. Therefore, the network is very small and doesn't bring any interesting insights. We don't extract users network for this topic.
* [Video recommendation network](https://mizvol.github.io/imi-nets/youtube/youtube-videos-haarp/)
* [Featured channels network](https://mizvol.github.io/imi-nets/youtube/youtube-channels-haarp/)

*YouTube data is collected using [YouTube Data Tools](https://github.com/bernorieder/YouTube-Data-Tools) by [Bernhard Rieder](http://thepoliticsofsystems.net/about/)
