# alt-music-player
Alternatively Styled Music Player

XML File Setup:
This player works with XML files.
Therefore the playlist and the
configuration of the player works
based on this XML file

Configuration:<br />
The configuration section holds data related to how main layout of the<br />
player, you could change specific items of the player.<br />
Here is the list of elements with appropriate values:<br />
Property Description Example<br />
artworkBlur Blurriness of the background artworks, integer/px. 5px<br />
autoplay First track of the playlist plays with the page load True/False<br />
shareButton Visibility of the share button in the player True/False<br />
muteButton Visibility of the mute button in the player True/False<br />
repeatButton Visibility of the repeat button in the player True/False<br />
shuffleButton Visibility of the shuffle button in the player True/False<br />
Playlist:<br />
Each that of the playlist must be inserted inside the playlist element of the xml<br />
file.<br />
For each track there are some properties that you can provide regarding the<br />
track.<br />
Property Description Example<br />
artist The name of the singer String<br />
title The track name String<br />
url The stream-able URL of the track URL<br />
artwork URL of the artwork of the track URL<br />
apple URL of the track in Apple Music URL<br />
amazon URL of the track in Amazon Music URL<br />
download Downloadable functionality True/False<br />
The ‘apple’ and ‘amazon’ properties are optimal and you can add them<br />
only if you have the URL of the tracks on these music websites. Therefore in<br />
case of not having the URL, you can simply remove these two elements from<br />
the track elements and it will not affect. As an example some tracks can be<br />
only downloadable, and some can have Amazon and Apple links, or some<br />
might have all of them.<br />
Furthermore, you can add as many tracks as you want.<br />

