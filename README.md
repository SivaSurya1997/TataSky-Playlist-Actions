# Tata Sky IPTV Playlist Generator Loop
This repository is for automatically generating playlist everyday with the same link. You don't need to use any app or anything, You just need to do this one-time setup and you're good to go.

## Prerequisites

* You need to have your own GitHub Token

* Tata Sky account details (Like Subscriber ID, Tata Sky Account Password, Tata Sky Registered Phone number)

* Your GitHub Email and UserID which you're using now

## How to use?

Steps:
1. First of all fork this repo.
2. Then go to Actions Tab in your forked-repo.
3. Now enter all your details.
4. Click on "Run Wokflow"
5. After clicking on Run Workflow, A new repository will be created in your account named "TataSkyIPTV-Daily"
6. Go to the new repository named "TataSkyIPTV-Daily"
7. Now under actions click on Run Workflow
8. Once the workflow has been successful, Check your GitHub gists [https://gist.github.com/] then click on view your Gists.
9. Now you'll see that you'll have allChannelPlaylist there.
10. Open it by clicking on it, Then tap on raw. Copy that link and then modify the link by removing only the the hashcode token after /raw/ in the URL.
11. There you go, Now use that URL in your Tivimate. And Tivimate will update the playlist automatically once you open the app.

## Explanation on how this works

This works purely on the basis of GitHub Workflow Actions, So a VERY BIG THANKS to GitHub.
I've created the script where Actions will automatically trigger the workflow everyday for 7:13 PM UTC.

The tokens, GitHub email and ID are required because we are basically creating another repo and gists with this script using them.

## Credits

* Gaurav Thakkar for his IPTV Repo
* GitHub for their GitHub Actions
