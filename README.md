# IPTV [![update](https://github.com/iptv-org/iptv/actions/workflows/update.yml/badge.svg)](https://github.com/iptv-org/iptv/actions/workflows/update.yml)

Collection of publicly available IPTV (Internet Protocol television) channels from all over the world.

## Table of contents

- 🚀 [How to use?](#how-to-use)
- 📺 [Playlists](#playlists)
- 🗓 [EPG](#epg)
- 🗄 [Database](#database)
- 👨‍💻 [API](#api)
- 📚 [Resources](#resources)
- 💬 [Discussions](#discussions)
- ❓ [FAQ](#faq)
- 🛠 [Contribution](#contribution)
- ⚖ [Legal](#legal)
- © [License](#license)

## How to use?

Simply insert one of the links below into [any video player](https://github.com/iptv-org/awesome-iptv#apps) that supports live streaming and press _Open_.

![VLC Network Panel](https://github.com/iptv-org/iptv/raw/master/.readme/preview.png)

## Playlists

There are several versions of playlists that differ in the way they are grouped. As of January 30th, 2024, we have stopped distributing NSFW channels. For more information, please look at [this issue](https://github.com/iptv-org/iptv/issues/15723).

### Main playlist

This playlist includes all known channels available in this repository.

```
https://artofknot.com/index.language.m3u
```

### Grouped by category

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _category_ as a group title:

```
https://artofknot.com/index.category.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
<table>
  <thead>
    <tr><th align="left">Category</th><th align="left">Channels</th><th align="left">Playlist</th></tr>
  </thead>
  <tbody>
    <tr><td>Business</td><td align="right">71</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/business.m3u</code></td></tr>
    <tr><td>Classic</td><td align="right">40</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/classic.m3u</code></td></tr>
    <tr><td>Comedy</td><td align="right">70</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/comedy.m3u</code></td></tr>
    <tr><td>Cooking</td><td align="right">29</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/cooking.m3u</code></td></tr>
    <tr><td>Culture</td><td align="right">171</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/culture.m3u</code></td></tr>
    <tr><td>Documentary</td><td align="right">101</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/documentary.m3u</code></td></tr>
    <tr><td>Education</td><td align="right">160</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/education.m3u</code></td></tr>
    <tr><td>Entertainment</td><td align="right">561</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/entertainment.m3u</code></td></tr>
    <tr><td>Family</td><td align="right">47</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/family.m3u</code></td></tr>
    <tr><td>General</td><td align="right">2375</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/general.m3u</code></td></tr>
    <tr><td>Kids</td><td align="right">227</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/kids.m3u</code></td></tr>
    <tr><td>Legislative</td><td align="right">190</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/legislative.m3u</code></td></tr>
    <tr><td>Lifestyle</td><td align="right">90</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/lifestyle.m3u</code></td></tr>
    <tr><td>Movies</td><td align="right">279</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/movies.m3u</code></td></tr>
    <tr><td>Music</td><td align="right">664</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/music.m3u</code></td></tr>
    <tr><td>News</td><td align="right">771</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/news.m3u</code></td></tr>
    <tr><td>Outdoor</td><td align="right">44</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/outdoor.m3u</code></td></tr>


  </tbody>
</table>

</details>

### Grouped by language

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _language_ as a group title:

```
https://artofknot.com/index.language.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
<table>
  <thead>
    <tr><th align="left">Language</th><th align="left">Channels</th><th align="left">Playlist</th></tr>
  </thead>
  <tbody>
   
    <tr><td align="left">Turkish</td><td align="right">246</td><td align="left" nowrap><code>https://artofknot.com/playlist.m3u</code></td></tr>
    <tr><td align="left">Turkmen</td><td align="right">8</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/tuk.m3u</code></td></tr>
    <tr><td align="left">Uighur</td><td align="right">3</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/uig.m3u</code></td></tr>
    <tr><td align="left">Ukrainian</td><td align="right">61</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/ukr.m3u</code></td></tr>
    <tr><td align="left">Urdu</td><td align="right">39</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/urd.m3u</code></td></tr>
    <tr><td align="left">Uzbek</td><td align="right">14</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/uzb.m3u</code></td></tr>
    <tr><td align="left">Vietnamese</td><td align="right">63</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/vie.m3u</code></td></tr>
    <tr><td align="left">Welsh</td><td align="right">1</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/cym.m3u</code></td></tr>
    <tr><td align="left">Western Frisian</td><td align="right">1</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/fry.m3u</code></td></tr>
    <tr><td align="left">Wolof</td><td align="right">7</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/wol.m3u</code></td></tr>
    <tr><td align="left">Yakut</td><td align="right">1</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/sah.m3u</code></td></tr>
    <tr><td align="left">Yoruba</td><td align="right">1</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/yor.m3u</code></td></tr>
    <tr><td align="left">Yucatec Maya</td><td align="right">1</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/yua.m3u</code></td></tr>
    <tr><td align="left">Yue Chinese</td><td align="right">7</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/yue.m3u</code></td></tr>
    <tr><td align="left">Zarma</td><td align="right">1</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/dje.m3u</code></td></tr>
    <tr><td align="left">Undefined</td><td align="right">2400</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/undefined.m3u</code></td></tr>
  </tbody>
</table>

</details>

### Grouped by country

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _country_ as a group title:

```
https://artofknot.com/index.country.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
<table>
  <thead>
    <tr><th align="left">Country</th><th align="left">Channels</th><th align="left">Playlist</th></tr>
  </thead>
  <tbody>
   
    <
    
    <tr><td>🇸🇩 Sudan</td><td align="right">56</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/sd.m3u</code></td></tr>
    <tr><td>🇸🇷 Suriname</td><td align="right">10</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/sr.m3u</code></td></tr>
    <tr><td>🇸🇿 Swaziland</td><td align="right">21</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/sz.m3u</code></td></tr>
    <tr><td>🇸🇪 Sweden</td><td align="right">71</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/se.m3u</code></td></tr>
    <tr><td>🇨🇭 Switzerland</td><td align="right">303</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/ch.m3u</code></td></tr>
    <tr><td>🇸🇾 Syria</td><td align="right">40</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/sy.m3u</code></td></tr>
    <tr><td>🇹🇼 Taiwan</td><td align="right">72</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/tw.m3u</code></td></tr>
    <tr><td>🇹🇯 Tajikistan</td><td align="right">32</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/tj.m3u</code></td></tr>
    <tr><td>🇹🇿 Tanzania</td><td align="right">29</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/tz.m3u</code></td></tr>
    <tr><td>🇹🇭 Thailand</td><td align="right">84</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/th.m3u</code></td></tr>
    <tr><td>🇹🇬 Togo</td><td align="right">33</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/tg.m3u</code></td></tr>
    <tr><td>🇹🇰 Tokelau</td><td align="right">9</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/tk.m3u</code></td></tr>
    <tr><td>🇹🇴 Tonga</td><td align="right">9</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/to.m3u</code></td></tr>
    <tr><td>🇹🇹 Trinidad and Tobago</td><td align="right">20</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/tt.m3u</code></td></tr>
    <tr><td>🇹🇳 Tunisia</td><td align="right">55</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/tn.m3u</code></td></tr>
    <tr><td>🇹🇷 Turkey</td><td align="right">276</td><td nowrap><code>https://artofknot.com/playlist.m3u</code></td></tr>
    <tr><td>🇹🇲 Turkmenistan</td><td align="right">17</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/tm.m3u</code></td></tr>

  </tbody>
</table>

</details>

### Grouped by region

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _region_ as a group title:

```
https://artofknot.com/index.region.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
<table>
  <thead>
    <tr><th align="left">Region</th><th align="left">Channels</th><th align="left">Playlist</th></tr>
  </thead>
  <tbody>
    <tr><td align="left">Africa</td><td align="right">515</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/afr.m3u</code></td></tr>
    <tr><td align="left">Americas</td><td align="right">4525</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/amer.m3u</code></td></tr>
    <tr><td align="left">Arab world</td><td align="right">357</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/arab.m3u</code></td></tr>
    <tr><td align="left">Asia</td><td align="right">2612</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/asia.m3u</code></td></tr>
    <tr><td align="left">Asia-Pacific</td><td align="right">1678</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/apac.m3u</code></td></tr>
    <tr><td align="left">Association of Southeast Asian Nations</td><td align="right">338</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/asean.m3u</code></td></tr>
    <tr><td align="left">Balkan</td><td align="right">647</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/balkan.m3u</code></td></tr>
    <tr><td align="left">Benelux</td><td align="right">247</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/benelux.m3u</code></td></tr>
    <tr><td align="left">Caribbean</td><td align="right">372</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/carib.m3u</code></td></tr>
    <tr><td align="left">Central America</td><td align="right">317</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/cenamer.m3u</code></td></tr>
    <tr><td align="left">Central and Eastern Europe</td><td align="right">1047</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/cee.m3u</code></td></tr>
    <tr><td align="left">Central Asia</td><td align="right">77</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/cas.m3u</code></td></tr>
    <tr><td align="left">Commonwealth of Independent States</td><td align="right">383</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/cis.m3u</code></td></tr>
    <tr><td align="left">Europe</td><td align="right">4060</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/eur.m3u</code></td></tr>
    <tr><td align="left">Europe, the Middle East and Africa</td><td align="right">4933</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/emea.m3u</code></td></tr>
    <tr><td align="left">European Union</td><td align="right">2853</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/eu.m3u</code></td></tr>
    <tr><td align="left">Hispanic America</td><td align="right">1858</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/hispam.m3u</code></td></tr>
    <tr><td align="left">Latin America</td><td align="right">2150</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/latam.m3u</code></td></tr>
    <tr><td align="left">Latin America and the Caribbean</td><td align="right">2185</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/lac.m3u</code></td></tr>
    <tr><td align="left">Maghreb</td><td align="right">47</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/maghreb.m3u</code></td></tr>
    <tr><td align="left">Middle East</td><td align="right">711</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/mideast.m3u</code></td></tr>
    <tr><td align="left">Middle East and North Africa</td><td align="right">743</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/mena.m3u</code></td></tr>
    <tr><td align="left">Nordics</td><td align="right">94</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/nord.m3u</code></td></tr>
    <tr><td align="left">North America</td><td align="right">3216</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/noram.m3u</code></td></tr>
    <tr><td align="left">Northern America</td><td align="right">2350</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/nam.m3u</code></td></tr>
    <tr><td align="left">Northern Europe</td><td align="right">138</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/neur.m3u</code></td></tr>
    <tr><td align="left">Oceania</td><td align="right">103</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/oce.m3u</code></td></tr>
    <tr><td align="left">South America</td><td align="right">1327</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/southam.m3u</code></td></tr>
    <tr><td align="left">South Asia</td><td align="right">425</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/sas.m3u</code></td></tr>
    <tr><td align="left">Southeast Asia</td><td align="right">346</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/sea.m3u</code></td></tr>
    <tr><td align="left">Southern Europe</td><td align="right">1149</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/ser.m3u</code></td></tr>
    <tr><td align="left">Sub-Saharan Africa</td><td align="right">444</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/ssa.m3u</code></td></tr>
    <tr><td align="left">West Africa</td><td align="right">200</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/wafr.m3u</code></td></tr>
    <tr><td align="left">Western Europe</td><td align="right">1718</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/wer.m3u</code></td></tr>
  </tbody>
</table>

</details>

## EPG

[Electronic Program Guide](https://en.wikipedia.org/wiki/Electronic_program_guide) for most of the channels can be downloaded using utilities published in the [iptv-org/epg](https://github.com/iptv-org/epg) repository.

## Database

All channel data is taken from the [iptv-org/database](https://github.com/iptv-org/database) repository. If you find any errors please open a new [issue](https://github.com/iptv-org/database/issues) there.

## API

The API documentation can be found in the [iptv-org/api](https://github.com/iptv-org/api) repository.

## Resources

Links to other useful IPTV-related resources can be found in the [iptv-org/awesome-iptv](https://github.com/iptv-org/awesome-iptv) repository.

## Discussions

If you need help finding a channel, have a question or idea, welcome to the [Discussions](https://github.com/orgs/iptv-org/discussions).

## FAQ

The answers to the most popular questions can be found in the [FAQ.md](FAQ.md) file.

## Contribution

Please make sure to read the [Contributing Guide](CONTRIBUTING.md) before sending an issue or making a pull request.

And thank you to everyone who has already contributed!

### Backers

<a href="https://opencollective.com/iptv-org"><img src="https://opencollective.com/iptv-org/backers.svg?width=890" /></a>

### Contributors

<a href="https://github.com/iptv-org/iptv/graphs/contributors"><img src="https://opencollective.com/iptv-org/contributors.svg?width=890" /></a>

## Legal

No video files are stored in this repository. The repository simply contains user-submitted links to publicly available video stream URLs, which to the best of our knowledge have been intentionally made publicly by the copyright holders. If any links in these playlists infringe on your rights as a copyright holder, they may be removed by sending a [pull request](https://github.com/iptv-org/iptv/pulls) or opening an [issue](https://github.com/iptv-org/iptv/issues/new?assignees=freearhey&labels=removal+request&template=--removal-request.yml&title=Remove%3A+). However, note that we have **no control** over the destination of the link, and just removing the link from the playlist will not remove its contents from the web. Note that linking does not directly infringe copyright because no copy is made on the site providing the link, and thus this is **not** a valid reason to send a DMCA notice to GitHub. To remove this content from the web, you should contact the web host that's actually hosting the content (**not** GitHub, nor the maintainers of this repository).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](LICENSE)
