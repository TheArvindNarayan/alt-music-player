# alt-music-player
Alternatively Styled Music Player

XML File Setup:
This player works with XML files.
Therefore the playlist and the
configuration of the player works
based on this XML file

Configuration:
The configuration section holds data related to how main layout of the
player, you could change specific items of the player.
Here is the list of elements with appropriate values:
Property Description Example
artworkBlur Blurriness of the background artworks, integer/px. 5px
autoplay First track of the playlist plays with the page load True/False
shareButton Visibility of the share button in the player True/False
muteButton Visibility of the mute button in the player True/False
repeatButton Visibility of the repeat button in the player True/False
shuffleButton Visibility of the shuffle button in the player True/False
Playlist:
Each that of the playlist must be inserted inside the playlist element of the xml
file.
For each track there are some properties that you can provide regarding the
track.
Property Description Example
artist The name of the singer String
title The track name String
url The stream-able URL of the track URL
artwork URL of the artwork of the track URL
apple URL of the track in Apple Music URL
amazon URL of the track in Amazon Music URL
download Downloadable functionality True/False
The ‘apple’ and ‘amazon’ properties are optimal and you can add them
only if you have the URL of the tracks on these music websites. Therefore in
case of not having the URL, you can simply remove these two elements from
the track elements and it will not affect. As an example some tracks can be
only downloadable, and some can have Amazon and Apple links, or some
might have all of them.
Furthermore, you can add as many tracks as you want.

