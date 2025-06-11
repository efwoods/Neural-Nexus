I am creating an application that will allow users to create individual avatars.

The mongo_db will have a collection per user. Inside this collection will be an avatar collection for each avatar the user has created. Inside the avatar collection are all text messages in each conversation and all media associated per avatar.

I have attached an image of the UI. The user experience is the following:
1. The user logs in.
2. The user's profile information is pulled from the postgres_db. All associated avatars per user are pulled from the postgres_db as well and populated in the left sidebar.
3. The user creates an avatar by sending the avatar's name and description. This creates the avatar in the postgres_db & populates the avatar in the left sidebar. 

4. If avatars have already been created, the user selects an avatar in the left sidebar. This searches the redis cache for the avatar information. If not found, the mongo_db is called to gather the avatar information which includes all previous messages between the user and the avatar. A message may include either text or media. Media includes audio, video, images, text files, numpy files, and other neural-data file types. This information is pulled into the redis cache and the previous messages are presented in the message window. When a user selects a new avatar, this information is again pulled from the redis cache or the mongo_db if not in the cache, stored in the cache, then presented in the frontend.


