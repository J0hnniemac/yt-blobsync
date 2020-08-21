# yt-blobsync
Repo in Support of YouTube video with BlobSync Script.

https://github.com/J0hnniemac/yt-blobsync

# YouTube Video
https://youtu.be/_7gNtFMUu18

# YouTube Video Description
In this video I create a Docker-ised script to syncronise Azure Blob Storage between Storage Accounts. I should some of the bumps in the road that caught me out.

This script could be used for scheduling sync between different storage accounts.

File are stored on github
https://github.com/J0hnniemac/yt-blobsync

This is my first technical video or article I have done since 2013 when I used to write on my blog http://www.networking-guru.net/

or back from early PacketPusher / Etherealmind days
https://etherealmind.com/how-long-does-it-take-to-become-a-ccie-from-0/


I would love to here your feedback below and if there are any other area that you think I should look into, drop me a note in the comments.

(I am just starting to get into Azure)


# Other things to do
If you delete a blob container in source, it will not be replicated at the destination. You could add this functionality after sync of existing containers are complete.

You propapbly don't need to genereate a SAS token for every Blob Container, depend how long the copy takes. Just create a longer timed SAS Token.
