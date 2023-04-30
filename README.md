
# All M3U Tags For IPTV Playlist

The M3U file format is a popular way of creating playlists for media players, including IPTV players. These playlists can be used to organize and customize the playback experience of various types of media, including video and audio files, and IPTV streams.



## EXT Tags
| EXT | Meaning |
| --- | ------- |
| #EXTM3U | Indicates that the file is an M3U playlist file |
| #EXTINF | Specifies the duration and title of a media file in the playlist |
| #EXT-X-VERSION | Indicates the version of the HLS protocol used in the playlist |
| #EXT-X-TARGETDURATION | Specifies the maximum duration of any media file in the playlist |
| #EXT-X-MEDIA-SEQUENCE | Specifies the sequence number of the first media file in the playlist |
| #EXT-X-PLAYLIST-TYPE | Indicates the type of playlist, such as "VOD" (video on demand) or "EVENT" |
| #EXT-X-ALLOW-CACHE | Indicates whether the client is allowed to cache the media files |
| #EXT-X-STREAM-INF | Specifies the URI of a variant stream playlist and its properties |
| #EXT-X-MEDIA | Specifies the URI of a media file and its properties |
| #EXT-X-KEY | Specifies encryption information for media files in the playlist |
| #EXT-X-BYTERANGE | Specifies the byte range of a media file in the playlist |
| #EXT-X-DISCONTINUITY | Indicates a discontinuity between two media segments |
| #EXT-X-DISCONTINUITY-SEQUENCE | Specifies the sequence number of the next media file after a discontinuity |
| #EXT-X-PROGRAM-DATE-TIME | Specifies the date and time of the first sample in a media file |
| #EXT-X-INDEPENDENT-SEGMENTS | Indicates whether each media file is a standalone segment or part of a larger media file |
| #EXT-X-ENDLIST | Indicates the end of the playlist |
| #EXT-X-MAP | Specifies the media initialization section for a media file |
| #EXT-X-START | Specifies the time offset and precise start time for a live event |
| #EXT-X-RENDITION-REPORT | Specifies the availability and properties of alternate renditions of a media file |
| #EXT-X-MEDIA-SEQUENCE-DISCONTINUITY | Indicates a discontinuity in the media sequence number |
| #EXT-X-DATERANGE | Specifies a range of dates for a media file or playlist |
| #EXT-X-TARGETDURATION-REACHED | Indicates that the maximum duration of a media file has been reached |
| #EXT-X-SERVER-CONTROL | Specifies server-side control parameters for the playlist |
| #EXT-X-VERSIONING | Specifies versioning information for the playlist |
| #EXT-X-I-FRAMES-ONLY | Indicates that the playlist contains only I-frame media files |
| #EXT-X-INDEPENDENT-SEGMENTS-DISCONTINUITY | Indicates a discontinuity in the independent segments |
| #EXT-X-SESSION-DATA | Specifies arbitrary data associated with the playlist |
| #EXT-X-SESSION-KEY | Specifies encryption information for the entire session |
| #EXT-X-PRELOAD-HINT | Indicates media files that the client should preload |
| #EXT-X-RENDITION-GROUP-ID | Identifies a group of alternate renditions |
| #EXT-X-RENDITION-LANGUAGE | Specifies the language of an alternate rendition |
| #EXT-X-RENDITION-ASSOCIATED-PROPERTY | Specifies a property associated with an alternate rendition |
| #EXT-X-RENDITION-URI | Specifies the URI of an alternate rendition |
| #EXT-X-CUE-OUT | Indicates the start time of a commercial break |
| #EXT-X-CUE-IN | Indicates the end time of a commercial break |
| #EXT-X-RENDITION-GROUP | Identifies a group of alternate renditions |
| #EXT-X-RENDITION-TO-PROGRAM | Specifies the mapping from a rendition to a program |
| #EXT-X-PROGRAM-DATE-TIME-OFFSET | Specifies the offset of the date and time for a live event |
| #EXT-X-CONTENT-IDENTIFIER | Specifies a unique identifier for a media file or playlist |
| #EXT-X-DATERANGE-ID | Specifies the identifier for a date range |
| #EXT-X-SERVER-CONTROL-COMMAND | Specifies a command to be sent to the server |
| #EXT-X-SERVER-CONTROL-HOLD-BACK | Specifies the amount of time to hold back media files |
| #EXT-X-SERVER-CONTROL-PART-HOLD-BACK | Specifies the amount of time to hold back partial media files |
| #EXT-X-SERVER-CONTROL-MAX-DURATION | Specifies the maximum duration of media files to send |
| #EXT-X-SERVER-CONTROL-MAX-AGE | Specifies the maximum age of cached media files |
| #EXT-X-SERVER-CONTROL-CAN-SKIP-UNTIL | Specifies the earliest time to skip to in a media file |
| #EXT-X-SERVER-CONTROL-CAN-SKIP-DATERANGES | Specifies whether the client can skip date ranges |
| #EXT-X-START-DURATION | Specifies the duration of a live event |
| #EXT-X-CUE-OUT-CONT-DURATION | Specifies the duration of a partial cue-out |
| #EXT-X-PROGRAM-DATE-TIME-SERVER | Specifies the date and time of the server |
| #EXT-X-CONTENT-KEY | Specifies a content key for a media file or playlist |
| #EXT-X-DISCONTINUITY-ITEM | Indicates a discontinuity between two media items |
| #EXT-X-SCTE35 | Specifies an SCTE-35 cue message |
| #EXT-X-CUE-OUT-PTS | Indicates the PTS value of a cue-out |
| #EXT-X-CUE-IN-PTS | Indicates the PTS value of a cue-in |
| #EXT-X-CUE-START-PTS | Indicates the PTS value of a cue-start |
| #EXT-X-CUE-END-PTS | Indicates the PTS value of a cue-end |
| #EXT-X-CUE-OUT-CONT-PTS | Indicates the PTS value of a partial cue-out |
| #EXT-X-MEDIA-RENDITION-REPORT | Specifies the availability and properties of alternate media renditions |
| #EXT-X-RELATIVE-CUE-OUT | Indicates the relative start time of a cue-out |
| #EXT-X-RELATIVE-CUE-IN | Indicates the relative end time of a cue-in |
| #EXT-X-RELATIVE-CUE-OUT-CONT | Indicates the relative start time and duration of a partial cue-out. |
| #EXT-X-MAP-BYTERANGE | Specifies the byte range of a media initialization section |
| #EXT-X-CUE-OUT-DURATION | Specifies the duration of a cue-out |
| #EXT-X-CUE-OUT-CONT-ID | Specifies the identifier of a partial cue-out |
| #EXT-X-CUE-IN-DURATION | Specifies the duration of a cue-in |
| #EXT-X-CUE-START-DURATION | Specifies the duration of a cue-start |
| #EXT-X-CUE-END-DURATION | Specifies the duration of a cue-end |
| #EXT-X-CUE-OUT-CONT-DURATION-MS | Specifies the duration of a partial cue-out in milliseconds |
