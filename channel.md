<table>
  <tbody>
    <tr>
      <td><b>id</b></td>
      <td>(Integer)</td>
      <td>The internal ID of the channel</td>
    </tr>
    <tr>
      <td><b>title</b></td>
      <td>(String)</td>
      <td>The title of the channel</td>
    </tr>
    <tr>
      <td><b>created_at</b></td>
      <td>(Timestamp)</td>
      <td>Timestamp when the channel was created</td>
    </tr>
    <tr>
      <td><b>updated_at</b></td>
      <td>(Timestamp)</td>
      <td>Timestamp when the channel was last updated</td>
    </tr>
    <tr>
      <td><b>published</b></td>
      <td>(Boolean)</td>
      <td>If channel is visible to all members of arena or not</td>
    </tr>
    <tr>
      <td><b>open</b></td>
      <td>(Boolean)</td>
      <td>If channel is open to other members of arena for adding blocks</td>
    </tr>
    <tr>
      <td><b>collaboration</b></td>
      <td>(Boolean)</td>
      <td>If the channel has collaborators or not</td>
    </tr>
    <tr>
      <td><b>slug</b></td>
      <td>(String)</td>
      <td>
        The slug of the channel used in the url (e.g.
        http://are.na/arena-influences)
      </td>
    </tr>
    <tr>
      <td><b>length</b></td>
      <td>(Integer)</td>
      <td>The number of items in a channel (blocks and other channels)</td>
    </tr>
    <tr>
      <td><b>kind</b></td>
      <td>(String)</td>
      <td>
        Can be either "default" (a standard channel) or "profile" the default
        channel of a user
      </td>
    </tr>
    <tr>
      <td><b>status</b></td>
      <td>(String)</td>
      <td>
        Can be "private" (only open for reading and adding to the channel by
        channel author and collaborators), "closed" (open for reading by
        everyone, only channel author and collaborators can add) or "public"
        (everyone can read and add to the channel)
      </td>
    </tr>
    <tr>
      <td><b>user_id</b></td>
      <td>(Integer)</td>
      <td>Internal ID of the channel author</td>
    </tr>
    <tr>
      <td><b>class</b></td>
      <td>(String)</td>
      <td>Will always be "Channel"</td>
    </tr>
    <tr>
      <td><b>base_class</b></td>
      <td>(String)</td>
      <td>Will always be "Channel"</td>
    </tr>
    <tr>
      <td><b>user</b></td>
      <td>(Hash)</td>
      <td>
        More information on the channel author. Contains <i>id</i>, <i>slug</i>,
        <i>first_name</i>, <i>last_name</i>, <i>full_name</i>, <i>avatar</i>,
        <i>email</i>, <i>channel_count</i>, <i>following_count</i>,
        <i>follower_count</i>, and <i>profile_id</i>
      </td>
    </tr>
    <tr>
      <td><b>total_pages</b></td>
      <td>(Integer)</td>
      <td>
        If pagination is used, how many total pages there are in your request
      </td>
    </tr>
    <tr>
      <td><b>current_page</b></td>
      <td>(Integer)</td>
      <td>If pagination is used, page requested</td>
    </tr>
    <tr>
      <td><b>per</b></td>
      <td>(Integer)</td>
      <td>If pagination is used, items per page requested</td>
    </tr>
    <tr>
      <td><b>follower_count</b></td>
      <td>(Integer)</td>
      <td>Number of followers the channel has</td>
    </tr>
    <tr>
      <td><b>contents</b></td>
      <td>(Array, can be null)</td>
      <td>
        Array of blocks and other channels in the channel. <b>Note:</b> If the
        request is authenticated, this will include any private channels
        included in the requested channel that you have access to. If not, only
        public channels included in the requested channel will be shown.
      </td>
    </tr>
    <tr>
      <td><b>collaborators</b></td>
      <td>(Array, can be null)</td>
      <td>Collaborators on the channel</td>
    </tr>
  </tbody>
</table>
