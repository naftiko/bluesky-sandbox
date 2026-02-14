# Bluesky API & MCP Sandbox
This is an API sandbox for the Bluesky API & MCP Sandbox, using an OpenAPI specification with examples, Microcks and Bruno as the sandbox interface, and this GitHub repository as the vehicle for delivering a localized sandbox.

## APIs.json
There is an APIs.yml file in the root of this repository, providing an index of all the artifacts used as part of this API sandbox, providing a machine-readable way to read, manage, and execute the sandbox available here.

## OpenAPI
This sandbox uses OpenAPI as the definition, providing [a complete definition of all available paths for the Bluesky API & MCP Sandbox. The OpenAPI for this sandnbox uses examples and Microcks extensions to mock the requests and responses for each API operation, something we will iterate and expand upon with richer examples as we move forward.

## Microcks
This sandbox uses Microcks to deliver the mock API. [You just install Microcks, with the Docker extension being the easiest](https://microcks.io/documentation/guides/installation/docker-desktop-extension/), [import the OpenAPI as a service](openapi/notion-openapi.yml), and you have a mocked API for all APIs, available via REST and MCP APIs--providing a multi-protocol sandbox.

## Bruno
This sandbox [uses Bruno as the client](https://www.usebruno.com/), leveraging Bruno Collections pre-generated from the OpenAPI and Bruno environments that uses the localhost and port of Microcks to work with the mocked API. You just have to install Microcks, then open the collection provided in this repository, select the available environment, and begin calling the Bluesky API & MCP Sandbox via the sandbox.

## Summary
This is a summary of this sandbox, breaking down the available paths, operations, and other relevant detail regarding the scope of this sandbox, designed to support development and testing against the Bluesky API & MCP Sandbox.

- Number of Paths: 168
- Number of Operations: 168
- Number of Read Operations: 93
- Number of Write Operations: 75
- Number of Schemas: 230
- Number of Responses: 0
- Number of Parameters: 0
- Number of Examples: 187
- Number of Request Bodies: 0
- Number of Headers: 0

## OpenAPIs
These are the OpenAPIs available for the Bluesky API & MCP Sandbox, which are made available via this sandbox API, which can be imported into Microcks and deployed as a sandbox using their mock feature.

  - [Bluesky Social Api](openapi/bluesky-openapi.yml)

## Resources
These are the resources available via the Bluesky API & MCP Sandbox, which are made available via this sandbox API, which are applied as tags to each operation in the OpenAPI.

  - Actor Profiles
  - Administration
  - Chat Actors
  - Chat Moderation
  - Content Labels
  - Conversations
  - Feeds
  - Identity
  - Labels
  - Moderation
  - Notifications
  - Ozone Communication
  - Ozone Moderation
  - Ozone Server
  - Ozone Sets
  - Ozone Settings
  - Ozone Signatures
  - Ozone Team
  - Repository
  - Server
  - Social Graph
  - Sync
  - Video

## Operations
These are all of the available operations in this sandbox, providing a complete view of what you can do within this sandbox using the mocked Bluesky API & MCP Sandbox.

  - Activates A Currently Deactivated Account.
  - Add A Member To The Ozone Team.
  - Add Values To A Specific Set.
  - Administrative Action To Create A New, Re-usable Communication (email For Now) Template.
  - Administrative Action To Update An Account's Email.
  - Administrative Action To Update An Account's Handle.
  - Administrative Action To Update An Existing Communication Template.
  - Apply A Batch Transaction Of Repository Creates, Updates, And Deletes.
  - Confirm An Email Using A Token From Com.atproto.server.requestemailconfirmation.
  - Count The Number Of Unread Notifications For The Requesting Account.
  - Create A Single New Repository Record.
  - Create An App Password.
  - Create An Account.
  - Create An Authentication Session.
  - Create An Invite Code.
  - Create Invite Codes.
  - Create Or Update Set Metadata
  - Create Or Update Setting Option
  - Creates A Mute Relationship For The Specified Account.
  - Creates A Mute Relationship For The Specified List Of Accounts.
  - Deactivates A Currently Active Account.
  - Delete A Communication Template.
  - Delete A Member From Ozone Team.
  - Delete A Repository Record, Or Ensure It Doesn't Exist.
  - Delete A User Account As An Administrator.
  - Delete An Actor's Account With A Token And Password.
  - Delete An Entire Set.
  - Delete Settings By Key
  - Delete The Current Session.
  - Delete Values From A Specific Set.
  - Describe The Credentials That Should Be Included In The Did Doc Of An Account That Is Migrating T...
  - Describes The Server's Account Creation Requirements And Capabilities.
  - Disable An Account From Receiving New Invite Codes, But Does Not Invalidate Existing Codes.
  - Disable Some Set Of Codes And/or All Codes Associated With A Set Of Users.
  - Enumerate Notifications For The Requesting Account.
  - Enumerates Accounts That The Requesting Account (actor) Currently Has Muted.
  - Enumerates Accounts Which A Specified Account (actor) Follows.
  - Enumerates Accounts Which Follow A Specified Account (actor) And Are Followed By The Viewer.
  - Enumerates Accounts Which Follow A Specified Account (actor).
  - Enumerates Follows Similar To A Given Account (actor).
  - Enumerates Mod Lists That The Requesting Account (actor) Currently Has Muted.
  - Enumerates Public Relationships Between One Account, And A List Of Other Accounts.
  - Enumerates The Lists Created By A Specified Account (actor).
  - Enumerates Which Accounts The Requesting Account Is Currently Blocking.
  - Find Actor Suggestions For A Prefix Search Term.
  - Find Actors (profiles) Matching Search Criteria.
  - Find All Correlated Threat Signatures Between 2 Or More Accounts.
  - Find Labels Relevant To The Provided At-uri Patterns.
  - Find Posts Matching Search Criteria, Returning Views Of Those Posts.
  - Find Repositories Based On A Search Term.
  - Get A Feed Of Recent Posts From A List (posts And Reposts From Any Actors On The List).
  - Get A Hydrated Feed From An Actor's Selected Feed Generator.
  - Get A List Of Feeds (feed Generator Records) Created By The Actor (in The Actor's Repo).
  - Get A List Of Posts Liked By An Actor.
  - Get A List Of Quotes For A Given Post.
  - Get A List Of Reposts For A Given Post.
  - Get A List Of Starter Packs Created By The Actor.
  - Get A List Of Suggested Actors.
  - Get A List Of Suggested Feeds (feed Generators) For The Requesting Account.
  - Get A Signed Token On Behalf Of The Requesting Did For The Requested Service.
  - Get A Single Record From A Repository.
  - Get A Skeleton Of A Feed Provided By A Feed Generator.
  - Get A Specific Set And Its Values
  - Get A View Of An Actor's 'author Feed' (post And Reposts By The Author).
  - Get A View Of The Requesting Account's Home Timeline.
  - Get Accounts That Share Some Matching Threat Signatures With The Root Account.
  - Get All Invite Codes For The Current Account.
  - Get An Admin View Of Invite Codes.
  - Get Detailed Profile View Of An Actor.
  - Get Detailed Profile Views Of Multiple Actors.
  - Get Details About A Moderation Event.
  - Get Details About A Record.
  - Get Details About A Repository.
  - Get Details About An Account.
  - Get Details About Ozone's Server Configuration.
  - Get Details About Some Accounts.
  - Get Details About Some Records.
  - Get Details About Some Repositories.
  - Get Information About A Feed Generator, Including Policies And Offered Feed Uris.
  - Get Information About A Feed Generator.
  - Get Information About A List Of Feed Generators.
  - Get Information About A List Of Labeler Services.
  - Get Information About An Account And Repository, Including The List Of Collections.
  - Get Information About The Current Auth Session.
  - Get Like Records Which Reference A Subject (by At-uri And Cid).
  - Get List Of Accounts That Matches Your Search Query.
  - Get List Of All Communication Templates.
  - Get Mod Lists That The Requesting Account (actor) Is Blocking.
  - Get Posts In A Thread.
  - Get Private Preferences Attached To The Current Account.
  - Get Status Details For A Video Processing Job.
  - Get The Service-specific Admin Status Of A Subject (account, Record, Or Blob).
  - Get Video Upload Limits For The Authenticated User.
  - Get Views For A List Of Starter Packs.
  - Gets A 'view' (with Additional Context) Of A Specified List.
  - Gets A View Of A Starter Pack.
  - Gets Post Views For A Specified List Of Posts (by At-uri).
  - Import A Repo In The Form Of A Car File.
  - Initiate A User Account Deletion Via Email.
  - Initiate A User Account Password Reset Via Email.
  - List A Range Of Records In A Repository, Matching A Specific Collection.
  - List All App Passwords.
  - List All Members With Access To The Ozone Service.
  - List Moderation Events Related To A Subject.
  - List Settings With Optional Filtering
  - Mutes A Thread Preventing Notifications From The Thread And Any Of Its Children.
  - Notify Server That The Requesting Account Has Seen Notifications.
  - Operation
  - Operation
  - Operation
  - Operation
  - Operation
  - Operation
  - Operation
  - Operation
  - Operation
  - Operation
  - Operation
  - Operation
  - Operation
  - Operation
  - Operation
  - Operation
  - Operation
  - Query Available Sets
  - Re-enable An Account's Ability To Receive Invite Codes.
  - Refresh An Authentication Session.
  - Register To Receive Push Notifications, Via A Specified Service, For The Requesting Account.
  - Request A Token In Order To Update Email.
  - Request An Email With A Code To Confirm Ownership Of Email.
  - Request An Email With A Code To In Order To Request A Signed Plc Operation.
  - Reserve A Repo Signing Key, For Use With Account Creation.
  - Reset A User Account Password Using A Token.
  - Resolves A Handle (domain Name) To A Did.
  - Returns A List Of Missing Blobs For The Requesting Account.
  - Returns The Status Of An Account, Especially As Pertaining To Import Or Recovery.
  - Revoke An App Password By Name.
  - Search For Accounts That Match One Or More Threat Signature Values.
  - Send Email To A User's Account Email Address.
  - Send Information About Interactions With Feed Items Back To The Feed Generator That Served Them.
  - Set Notification-related Preferences For An Account.
  - Set The Private Preferences Attached To The Account.
  - Signs A Plc Operation To Update Some Value(s) In The Requesting Did's Document.
  - Submit A Moderation Report Regarding An Atproto Account Or Record.
  - Take A Moderation Action On An Actor.
  - This Endpoint Is Part Of The Atproto Repository Synchronization Apis.
  - This Endpoint Is Part Of The Atproto Repository Synchronization Apis.
  - This Endpoint Is Part Of The Atproto Repository Synchronization Apis.
  - This Endpoint Is Part Of The Atproto Repository Synchronization Apis.
  - This Endpoint Is Part Of The Atproto Repository Synchronization Apis.
  - This Endpoint Is Part Of The Atproto Repository Synchronization Apis.
  - This Endpoint Is Part Of The Atproto Repository Synchronization Apis.
  - This Endpoint Is Part Of The Atproto Repository Synchronization Apis.
  - This Endpoint Is Part Of The Atproto Repository Synchronization Apis.
  - This Endpoint Is Part Of The Atproto Repository Synchronization Apis.
  - Unmutes The Specified Account.
  - Unmutes The Specified List Of Accounts.
  - Unmutes The Specified Thread.
  - Update A Member In The Ozone Service.
  - Update An Account's Email.
  - Update The Password For A User Account As An Administrator.
  - Update The Service-specific Admin Status Of A Subject (account, Record, Or Blob).
  - Updates The Current Account's Handle.
  - Upload A New Blob, To Be Referenced From A Repository Record.
  - Upload A Video To Be Processed Then Stored On The Pds.
  - Validates A Plc Operation To Ensure That It Doesn't Violate A Service's Constraints Or Get The Id...
  - View Moderation Statuses Of Subjects (record Or Repo).
  - Write A Repository Record, Creating Or Updating It As Needed.

## Backstage
We provide a Backstage software catalog entity for the Bluesky API & MCP Sandbox, allowing this sandbox to be registered with any catalog, making it discoverable by team and across an organization--allowing anyone to fork and deploy locally within the enterprise.

  - [Bluesky Social API](backstage/bluesky-api-sandbox-backstage.yml)
## Support
Please provide any questions or feedback via GitHub issues, or just email kinlane@naftiko.io with feedback. The goal is to keep iterating upon this sandbox using existing OpenAPI, Microcks, and Bruno features, offering value out of the box via this forkable third-party Bluesky API & MCP Sandbox.

