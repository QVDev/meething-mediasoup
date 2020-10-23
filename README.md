<img src="https://i.imgur.com/XS79fTC.png" width=200> <img  alt="mozilla-builders" src="https://user-images.githubusercontent.com/1423657/81992335-85346480-9643-11ea-8754-8275e98e06bc.png" width=100 />

### Meething MediaSoup

This is the awesome [mediasoup](https://mediasoup.org) multiroom server implementation for [meething](https://github.com/meething/meething) 

#### Why?
There are many servers like it, but this one provides transparent room and user routing based on `wss` URL parameters and LRU rooms

```
wss://meething-mediasoup:2345/?roomId=lobby&peerId=meMyselfandI
```

#### dWeb (wip)
The SFU will advertise itself to gun and/or hyperswarm dht peers for discovery by clients

#### Configuration
Configure your SSL certificates and preferences in `meething-mediasoup.config.js`

#### Service
```
pm2 start meething-mediasoup.config.js
```

#### Credits

* [MediaSoup](https://mediasoup.org) its Authors get all the credit for the SFU magic and their help
  * Iñaki Baz Castillo [[website](https://inakibaz.me)|[github](https://github.com/ibc/)]
  * José Luis Millán [[github](https://github.com/jmillan/)]
* The Meething team for their enthusiasm and ideas
* [Mozilla Builders](https://builders.mozilla.community) program and its mentors for the guidance

## Demo hosting
<a href="https://www.openode.io/">Cloud hosted on opeNode.io</a>


