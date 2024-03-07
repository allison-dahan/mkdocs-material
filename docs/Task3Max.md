# Live Share

When working remote with peers, you may want to work on the same codebase together. Live Share allows you to share your codebase with your team members via a secure connection. You are able to collaboratively edit multiple files in a workspace, and debug your application with your peers.

## Get started with Live Share

To use Live Share, you'll need to download the Live Share extension from the Extensions tab on your status bar.

![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1210310560533450752/image.png?ex=65ea188c&is=65d7a38c&hm=efc6a4f73b7b9cbf2d0f3f6a9cc942c28c4eaf157d2c5afda578dd34fdf58a03&){ align=left, width=800px }

This extension has everything you and your team or class need to edit and debug together in real time. With just one click, you can start working together on programming projects, reviewing code remotely, leading interactive lessons, and more, all without leaving VS Code.

Once you log into your GitHub account, you'll see the Live Share icon in the Activity Bar.

Simply click the newly added tab(1) on your status bar to open details for Live Share.
{ .annotate }

1.  ![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1210307240678920293/image.png?ex=65ea1574&is=65d7a074&hm=07b72e60b29337638152f98c4192ee8416d4e9695d0a7ae24b70e69bf2a129a8&){ align=left, width=50px } <br>Live Share button

## Usage

=== "Share"

    ### Starting a session

    1. Choose of of the two "Share" option from the Session Details menu.

        ![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1215356017915858944/image.png?ex=65fc737e&is=65e9fe7e&hm=21684b250797d2dbad2c9c3b3f84deac3f6cd407c739646581c7c934d5a7c401&){  width=500px }

        ??? tip "What is the difference between Read/Write and Read-Only?"

            * Read/Write allows others to edit your code space
            * Read-Only allows others to only view your code space


        Once your choose an option, your session link is instantly copied to your clipboard


    2. Share link as long as the other person have VS Code and the Live Share extension installed too.

        ![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1215358714480168990/image.png?ex=65fc7601&is=65ea0101&hm=0c246842eed62e45983aa734a2dca3583d93f1cb0e25600694071ea46b5db19c&)

    ### Accepting a session

    When someone requests to join your session, you will be greeted with a notification on the bottom right.

    1. You can either give them read-write or read only privileges, or reject if you don't know who this user is.

        ![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1215360734322626600/image.png?ex=65fc77e3&is=65ea02e3&hm=b04011892d7b2fbcd16d8cad6e4d1145586ca595f2d5dd9db4afe4cd8f751bbb&)

    ### Deleting a session

    Hover over the Session Details menu to show the "Stop Collaboration Session" button.

    1. Selecting it will terminate your session.

        ![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1215364452212285501/image.png?ex=65fc7b59&is=65ea0659&hm=b51114a954fc42e646d70ffcf469d3c73dfd80f74016169af77cce86e9e97a7e&)

=== "Join"

    ### Joining a session

    There are two ways of joining a session

    #### Joining via VS Code

    1. Choose the Join option from the Session Details menu.

        ![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1215356017915858944/image.png?ex=65fc737e&is=65e9fe7e&hm=21684b250797d2dbad2c9c3b3f84deac3f6cd407c739646581c7c934d5a7c401&){  width=500px }

    2. Enter the invite link that you've received to join session.

        ![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1215368696101470318/image.png?ex=65fc7f4d&is=65ea0a4d&hm=1bf0a5d2383dec7029f6cf79aa4b92ea0077da192d8c30f0d2c165b7fa671e79&)

    3. If you are logged into VS Code, then your request to join will be sent. All you have to do now is to wait for the acceptance and start collaborating!

    #### Joining via Browser

    1. Go to your desired browser and paste the invite link into the URL. You will be greeted with a window prompting you to choose to join by signing in or anonymously.

        ![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1215371224834773022/image.png?ex=65fc81a8&is=65ea0ca8&hm=a208bf447df8076ea7562ce46a37998bf4dc3f332ddeb50ef0ff2b65a9fd6d64&)

        ##### Sign in with Microsoft or VS Code

        Choose one of two options and you will be prompted with a popup sign in window.

        ![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1215371423472812072/image.png?ex=65fc81d7&is=65ea0cd7&hm=6f557be8b3d7ea32a9802d87da634844545de173ef3efbd1dfe45693068be7af&)

        ##### Join anonymously with a name

        Enter in a name for the session, press enter to confirm and esc for cancel.

        ![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1215371939338788934/image.png?ex=65fc8252&is=65ea0d52&hm=700383e1fb7b5a6264c90a3b2baae705d4d8624f61d93e7d17238bea2de1bc60&)

    2. Now just wait for acceptance and start collaborating!

    !!! success
        You will see a popup on the bottom right saying joining session if your request has been successfully sent out.

## Functionality

### Follow cursor

1. Begin a Live Share session.
2. Follow cursor by clicking on the participant's name on the Live Share extension sidebar. 
    ![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1215391343908495441/image.png?ex=65fc9465&is=65ea1f65&hm=87c909baac943bf62bfe35950e1de0efe396349ee65030d209042603e05fe73a&)
3. Now you are following that participant's cursor.

### Integrated chat support

1. Begin a Live Share session.
2. Utilize the built-in chat through the Live Share extension sidebar.
   ![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1215390008735699015/image.png?ex=65fc9326&is=65ea1e26&hm=5b151bfedd13603e5a1e0f3b91bc336456920049a273999e4bc9134e1bc5a52d&)
3. Communicate with collaborators without needing external tools.
   ![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1215390201518759946/image.png?ex=65fc9354&is=65ea1e54&hm=233e5555370fb64609ed78a504535270e0f286108b65e6920ff7ea0a9b4a664f&)

### Shared terminals and local server

1. The host starts a Live Share session and opens a terminal in VS Code.
2. Share access to the terminal or a local server with collaborators.
   ![Image title](https://media.discordapp.net/attachments/647920446649532417/1215390518213607426/image.png?ex=65fc93a0&is=65ea1ea0&hm=16e5cb969e64105759b6ef1ae159de0696d9be32fae8429f7429de935f55ab36&=&format=webp&quality=lossless&width=1156&height=679)
3. Perform tests and debug applications together, viewing real-time results in the shared environment.
   ![Image title](https://cdn.discordapp.com/attachments/647920446649532417/1215390675525439528/image.png?ex=65fc93c5&is=65ea1ec5&hm=5977195b8e4fbe5f4484280dc80479b70cfc3767a0e1fb58d14f00289826d530&)
