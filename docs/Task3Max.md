# Live Share

When working remote with peers, you may want to work on the same codebase together. Live Share allows you to share your codebase with your team members via a secure connection. You are able to collaboratively edit multiple files in a workspace, and debug your application with your peers.

## Get started with Live Share

To use Live Share, you'll need to download the Live Share extension from the Extensions tab on your status bar.

![Image title](/assets/images/downloadLiveshare.png){ align=left, width=800px }

This extension has everything you and your team or class need to edit and debug together in real time. With just one click, you can start working together on programming projects, reviewing code remotely, leading interactive lessons, and more, all without leaving VS Code.

Once you log into your GitHub account, you'll see the Live Share icon in the Activity Bar.

Simply click the newly added tab(1) on your status bar to open details for Live Share.
{ .annotate }

1.  ![Image title](/assets/images/liveshareButton.png){ align=left, width=50px } <br>Live Share button

## Usage

=== "Share"

    ### Starting a session

    1. Choose of of the two "Share" option from the Session Details menu.

        ![Image title](/assets/images/joinShare.png){  width=500px }

        ??? tip "What is the difference between Read/Write and Read-Only?"

            * Read/Write allows others to edit your code space
            * Read-Only allows others to only view your code space


        Once your choose an option, your session link is instantly copied to your clipboard


    2. Share link as long as the other person have VS Code and the Live Share extension installed too.

        ![Image title](/assets/images/linkCopiedInClipboard.png)

    ### Accepting a session

    When someone requests to join your session, you will be greeted with a notification on the bottom right.

    1. You can either give them read-write or read only privileges, or reject if you don't know who this user is.

        ![Image title](/assets/images/writeOrReadPrivilege.png)

    ### Deleting a session

    Hover over the Session Details menu to show the "Stop Collaboration Session" button.

    1. Selecting it will terminate your session.

        ![Image title](/assets/images/terminateSession.png)

=== "Join"

    ### Joining a session

    There are two ways of joining a session

    #### Joining via VS Code

    1. Choose the Join option from the Session Details menu.

        ![Image title](/assets/images/joinShare.png){  width=500px }

    2. Enter the invite link that you've received to join session.

        ![Image title](/assets/images/enterSessionLink.png)

    3. If you are logged into VS Code, then your request to join will be sent. All you have to do now is to wait for the acceptance and start collaborating!

    #### Joining via Browser

    1. Go to your desired browser and paste the invite link into the URL. You will be greeted with a window prompting you to choose to join by signing in or anonymously.

        ![Image title](/assets/images/joinBySignOrAnon.png)

        ##### Sign in with Microsoft or VS Code

        Choose one of two options and you will be prompted with a popup sign in window.

        ![Image title](/assets/images/signInLiveshare.png)

        ##### Join anonymously with a name

        Enter in a name for the session, press enter to confirm and esc for cancel.

        ![Image title](/assets/images/anonLiveshare.png)

    2. Now just wait for acceptance and start collaborating!

    !!! success
        You will see a popup on the bottom right saying joining session if your request has been successfully sent out.

## Functionality

### Follow cursor

1. Begin a Live Share session.
2. Follow cursor by clicking on the participant's name on the Live Share extension sidebar.
   ![Image title](/assets/images/followCursor.png)
3. Now you are following that participant's cursor.

### Integrated chat support

1. Begin a Live Share session.
2. Utilize the built-in chat through the Live Share extension sidebar.
   ![Image title](/assets/images/chatSupport.png)
3. Communicate with collaborators without needing external tools.
   ![Image title](/assets/images/chatBox.png)

### Shared terminals and local server

1. The host starts a Live Share session and opens a terminal in VS Code.
2. Share access to the terminal or a local server with collaborators.
   ![Image title](/assets/images/liveshareTerminal.png)
3. Perform tests and debug applications together, viewing real-time results in the shared environment.
   ![Image title](/assets/images/terminalLiveshare.png)
