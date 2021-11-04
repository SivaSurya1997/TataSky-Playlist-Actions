# Tata Sky Playlist Actions

### This repository is for automatically generating playlist for every 24hrs with the same link. You don't need to use any app or anything, You just need to do this one-time setup and you're good to go.

## Prerequisites

* You need to have your own GitHub Token
* For Token need to register on GITHUB, After login, Goto Setting=>Developer Options=>Personal access tokens.
 ![image](https://i.ibb.co/4mrVJpv/Github-Actions.png)


* Tata Sky account details (Like Subscriber ID, Tata Sky Account Password, Tata Sky Registered Phone number)

* Your GitHub Email and UserID which you're using now

## How to use?

Steps:
1. First of all fork this repo.
2. Then go to Actions Tab in your forked-repo. ![image](https://i.ibb.co/km2D2zJ/Trace-Actions.png)

3. Now enter all your details.
4. Click on "Run Wokflow"
5. After clicking on Run Workflow, A new repository will be created in your account named "TataSkyIPTV-Daily"
6. Go to the new repository named "TataSkyIPTV-Daily"
7. Now under actions click on Run Workflow
 ![image](https://i.ibb.co/YRZHFny/breh.png)

8. Once the workflow has been successful, Check your [GitHub gists](https://gist.github.com/) then click on view your Gists.
9. Now you'll see that you'll have allChannelPlaylist there.
10. Open it by clicking on it, Then tap on raw. Copy that link and then modify the link by removing only the the hashcode token after /raw/ in the URL.
11. There you go, Now use that URL in your Tivimate. And Tivimate will update the playlist automatically once you open the app.
12. ![image](https://user-images.githubusercontent.com/90518979/136909762-9fed542f-21cb-4194-a71f-79e6aa016b01.png)


Now you don't need to touch anything, It updates the playlist on it's own everyday and you only need to Update the playlist in Tivimate.
All the steps above are to be done only for once.

## Explanation on how this works

This works purely on the basis of GitHub Workflow Actions, So a VERY BIG THANKS to GitHub.
I've created the script where Actions will automatically trigger the workflow everyday for 2:30 AM IST.

The tokens, GitHub email and ID are required because we are basically creating another repo and gists with this script using them.

## Credits

* [Gaurav Thakkar](https://github.com/ForceGT) for his [IPTV Repo](https://github.com/ForceGT/Tata-Sky-IPTV)
* GitHub for their GitHub Actions
