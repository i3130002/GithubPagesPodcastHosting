# GithubPagesPodcastHosting
A GitHub repository for hosting podcasts

# [RSS.xml](https://i3130002.github.io/GithubPagesPodcastHosting/RSS.xml)

# Benefits
- Free for 10GB of total files
- Free bandwidth
- Free CDN
- The ability to change content after publish
- Control the order of episodes
- Free and open source

# Downsides
- No tracking
- Harder to setup and maintain than most podcast apps
- trust on Github(Microsoft)

# How to use it...
1- [Fork the repo](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)

2- [Github Pages](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)

3- Upload your icon and replace icon.jpg

3- Update the RSS.xml and basic information

3- Upload your audio inside [/media](https://github.com/i3130002/GithubPagesPodcastHosting/tree/main/media) folder of the repo 

4- Update the RSS.xml with episode information:
```xml
 <item>
      <author>Author</author>
      <itunes:author>Author</itunes:author>
      <title>Title</title>
      <pubDate>Mon, 13 Apr 2020 13:00:00 GMT</pubDate>
      <enclosure url="https://i3130002.github.io/media/Some large title at the begining (Episode 01).mp3" type="audio/mpeg" />
      <itunes:duration>54:08</itunes:duration>
      <guid isPermaLink="false">cepod01</guid>
      <itunes:explicit>no</itunes:explicit>
      <description>
        description of the episode
      </description>
    </item>
```

Make sure to add this after the last item before the `</channel>`





#### Special Thanks to
[rodydavis](https://github.com/rodydavis/podcast-player/tree/master)
