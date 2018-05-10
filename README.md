# GithubBot

Simple Github Bot for [Cisco Spark](https://developer.webex.com/)


The bot listens for commits and comments on a particular repo, and then posts the details into a group or team room. The below parameters will be included in the message to a Webex Teams space:

    Author Name
    Committer Name
    Pusher Name
    Commit id
    Commit time
    Repository
    Link to the Commit
    Comment
    Comment Link
    Comment User
    Repo
    Commit id
   
Note: You will need to set up webhook on Github for these events.
