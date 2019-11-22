# data-random-chat-apps

Dataset of iOS app reviews for random chat apps. Manually tagged reviews with "unwanted sexual behavior".

Story: `<insert story link here>`

Data: https://github.com/AlJohri/data-random-chat-apps/raw/master/reviews.csv

Apps: [Monkey](https://apps.apple.com/us/app/monkey/id1165924249), [Yubo](https://apps.apple.com/us/app/yubo-make-new-friends/id1038653883), [ChatLive](https://apps.apple.com/us/app/chatlive-random-video-chat/id1442099894), [Chat for Strangers](https://apps.apple.com/us/app/chat-for-strangers-video-chat/id447269854), [Skout](https://apps.apple.com/us/app/skout-meet-new-people/id302324249) and [Holla](https://apps.apple.com/us/app/holla-live-random-video-chat/id1125318983).

#### Data Dictionary

Column | Description
------ | ------------------
`reviewId`| Unique identifier for a review
`app`| Name of app
`date`| Date and time of review
`rating`| 1-5 rating
`userId`| Apple assigned user id
`userName`| User chosen nickname
`title`| Title of review
`body`| Main text of review
`sexually_explicit`| `1` if the review mentions something sexually explicit occurred or the review itself is sexually explicit, `0` if not, `?` if the the manual coder was unable to decide, and blank if the review was not manually coded.
`unwanted_sexual`| `1` if the review mentions that some unwanted sexual behavior occured or generally occurs, `0` if not, `?` if the the manual coder was unable to decide, and blank if the review was not manually coded.
`racism`| `1` if the review mentions that some racist behavior occured or the review itself is racist, `0` if not, `?` if the the manual coder was unable to decide, and blank if the review was not manually coded.
`bullying`| `1` if the review mentions that some form of bullying occured, `0` if not, `?` if the the manual coder was unable to decide, and blank if the review was not manually coded.
`spam`| `1` if the review talks about spammy behavior from the app, it's users, or other third-parties, `0` if not, `?` if the the manual coder was unable to decide, and blank if the review was not manually coded.


#### Summary of `unwanted_sexual` column

| App Name | Reviews With Unwanted Sexual Behavior | Reviews Without Unwanted Sexual Behavior | Reviews that the manual coder was unable to resolve | Untagged Reviews |
------|------|-------|--------------|----------|
| ChatForStrangers | 29 | 282 | 44 | 2823 | 3178 |
| ChatLive | 38 | 29 | 3 | 79 | 149 |
| Holla | 73 | 111 | 19 | 9919 | 10122 |
| Monkey | 842 | 531 | 179 | 26204 | 27756 |
| Skout | 690 | 551 | 254 | 84597 | 86092 |
| Yubo | 49 | 98 | 18 | 4287 | 4452 |
| All | 1721 | 1602 | 517 | 127909 | 131749 |
