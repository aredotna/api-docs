\*\*id\*\*

(Integer)

The internal ID of the channel

\*\*title\*\*

(String)

The title of the channel

\*\*created\_at\*\*

(Timestamp)

Timestamp when the channel was created

\*\*updated\_at\*\*

(Timestamp)

Timestamp when the channel was last updated

\*\*published\*\*

(Boolean)

If channel is visible to all members of arena or not

\*\*open\*\*

(Boolean)

If channel is open to other members of arena for adding blocks

\*\*collaboration\*\*

(Boolean)

If the channel has collaborators or not

\*\*slug\*\*

(String)

The slug of the channel used in the url (e.g. http://are.na/arena-influences)

\*\*length\*\*

(Integer)

The number of items in a channel (blocks and other channels)

\*\*kind\*\*

(String)

Can be either \\"default\\" (a standard channel) or \\"profile\\" the default channel of a user

\*\*status\*\*

(String)

Can be \\"private\\" (only open for reading and adding to the channel by channel author and collaborators), \\"closed\\" (open for reading by everyone, only channel author and collaborators can add) or \\"public\\" (everyone can read and add to the channel)

\*\*user\_id\*\*

(Integer)

Internal ID of the channel author

\*\*class\*\*

(String)

Will always be \\"Channel\\"

\*\*base\_class\*\*

(String)

Will always be \\"Channel\\"

\*\*user\*\*

(Hash)

More information on the channel author. Contains \_id\_, \_slug\_, \_first\_name\_, \_last\_name\_, \_full\_name\_, \_avatar\_, \_email\_, \_channel\_count\_, \_following\_count\_, \_follower\_count\_, and \_profile\_id\_

\*\*total\_pages\*\*

(Integer)

If pagination is used, how many total pages there are in your request

\*\*current\_page\*\*

(Integer)

If pagination is used, page requested

\*\*per\*\*

(Integer)

If pagination is used, items per page requested

\*\*follower\_count\*\*

(Integer)

Number of followers the channel has

\*\*contents\*\*

(Array, can be null)

Array of blocks and other channels in the channel. \*\*Note:\*\* If the request is authenticated, this will include any private channels included in the requested channel that you have access to. If not, only public channels included in the requested channel will be shown.

\*\*collaborators\*\*

(Array, can be null)

Collaborators on the channel
