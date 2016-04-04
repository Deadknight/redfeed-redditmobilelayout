RedFeed Reddit Mobile Layout Feed plugin template
=================================================

With this template you can create custom row plugins to RedFeed application.

https://play.google.com/store/apps/details?id=org.sombrenuit.dk.redfeed.free

How to
------

| name | description  |
|:---:|:---:|
| nameResourceString | Resource string of app name that shown on plugin selector | 
| layoutType | layout type 4 or 5. 4 for single column 5 for staggered grid | 
| layoutColumns | column count if layoutType is 5 and orientation is portrait | 
| layoutColumnsLandscape | column count if layoutType is 5 and orientation is landscape | 
| layoutXml | resource xml to inflate | 
| imageButUpvoteId | upvote button id | 
| tvScoreId | score textview id | 
| imageButDownvoteId | downvote button id | 
| ivImageId | thumbnail image id | 
| useBigThumbs | use big thumbs on image |
| tvTitleId | title id | 
| tvDetailId | detail id (not used for layout 6)  | 
| butCommentCountId | comment count button id | 
| butShareId | button share id | 
| butSaveId | button save id | 
| butHideId | button hide id | 
| imageButMoreId | imagebutton mode id | 
| tvUrlId | url textview id (not used for layout 4,5) | 
| tvDateId | date textview id  | 
| tvAuthorId | author textview id | 
| tvSubredditId | subreddit textview id | 
| clickId | id of the view that will open detail | 
| useDefaultImageOnLoad | use default image before image load (1 or 0) | 
| showCommentsText | show comments text on butCommentCountId (1 or 0) (if showCommentCountText is 0 this will be ignored) | 
| showCommentCountText | show comment count on butCommentCountId (1 or 0) | 
| upvoteDrawableId | custom upvote drawable id (if empty, default will be used)  | 
| upvoteSelectedDrawableId |  custom upvote selected drawable id (if empty, default will be used) | 
| downvoteDrawableId | custom downvote drawable id (if empty, default will be used) | 
| downvoteSelectedDrawableId | custom downvote selected drawable id (if empty, default will be used) | 
| upvoteColorId | custom upvote color id (if empty, default will be used) | 
| downvoteColorId | custom downvote color id (if empty, default will be used) | 
| novoteColorId | custom no vote color id (if empty, default will be used) |   | 
| defaultImageDrawableId | default image id which will be used if there are no thumbs | 
| defaultImageDarkDrawableId | dark theme image of defaultImageDrawableId | 
| selfImageDrawableId | self image id which will be used for self posts | 
| selfImageDarkDrawableId | dark theme image of selfImageDrawableId | 
| nsfwImageDrawableId | nsfw image id which will be used for nsfw posts | 
| nsfwImageDarkDrawableId | dark theme image of nsfwImageDrawableId |

- All of the id's are resources


