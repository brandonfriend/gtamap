The basic syntax of this file is pretty easy. Here are two examples:

##### Content with a video

      {
        "id":1,
        "type":"Wall breaches",
        "timestamp":"2014-06-30T20:52:43+00:00",
        "title":"Breach name",
        "notes":"Go to the location as seen below. First do this, then that and then do that.",
        "order":1,
        "lat":78.609,
        "lng":-120.454,
        "video":{
          "yt_id":"xXxXxXx123",
          "yt_user":"YouTube Account",
          "start":"0:10",
          "end":"0:30"
        },
        "credit":[
          {
            "what":"Glitch found",
            "who":"/u/reddituser",
            "where":"http://www.reddit.com/user/reddituser"
          }
        ]
      }

##### Content with images

      {
        "id":2,
        "type":"Wall breaches",
        "timestamp":"2014-06-30T20:52:43+00:00",
        "title":"Breach name",
        "notes":"Go to the location as seen below. First do this, then that and then do that.",
        "order":2,
        "lat":78.609,
        "lng":-120.454,
        "images":[
          {
            "id":"1",
            "headline":"Image headline",
            "url":"http://i.imgur.com/xTUJSve.jpg",
            "author":"/u/reddituser",
            "contact":"http://www.reddit.com/user/reddituser"
          },
          {
            "id":"2",
            "headline":"Second headline",
            "url":"http://i.imgur.com/wPWlH4v.jpg",
            "author":"/u/anotherreddituser",
            "contact":"http://www.reddit.com/user/anotherreddituser"
          }
        ],
        "credit":[
          {
            "what":"Glitch found",
            "who":"/u/reddituser",
            "where":"http://www.reddit.com/user/reddituser"
          }
        ]
      }