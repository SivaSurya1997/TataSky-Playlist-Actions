# Tata Sky Playlist Actions

### This repository is for automatically generating playlist for every 24hrs with the same link. You don't need to use any app or anything, You just need to do this one-time setup and you're good to go.

## Prerequisites

* You need to have your own GitHub Token
* For Token need to register on GITHUB, After login, Goto Setting=>Developer Options=>Personal access tokens.
 ![image](https://i.ibb.co/4mrVJpv/Github-Actions.png)

* Tata Sky account details (Like Subscriber ID, Tata Sky Account Password, Tata Sky Registered Phone number)

* Your GitHub Email and UserID which you're using now

## Steps for usage

1. First of all fork this repo.
2. Then go to Settings > Secrets > 'New Repository Secret'

   Now fill the values as described below!


   ```text
   GIT_ID : Enter your 'GitHub ID' in the values section.
   GIT_MAIL : Enter your 'GitHub name' in the values section.
   GIT_TOKEN : Enter your 'GitHub Token' in the values section.
   SUB_ID : Enter your 'TataSky Subscriber ID' in the values section.
   TATA_MOBILE : Enter your 'TataSky Mobile Number' in the values section.
   TATA_PASS : Enter your 'Tatasky Password' in the values section.
   ```
   Like this: ![image](https://i.ibb.co/Jq7wL1W/Screenshot-2021-11-10-164620.png)

   Total 6 values.

4. Now, go to 'Actions' Tab, Click on "Run Wokflow"
5. After clicking on Run Workflow, A new repository will be created in your account named "TataSkyIPTV-Daily". Now this is your 
6. Check your [GitHub gists](https://gist.github.com/) then click on 'view your Gists'.
7. Now you'll see that you'll have allChannelPlaylist there.
8. Open it by clicking on it, Then tap on raw. Copy that link and then modify the link by removing only the the hashcode token after /raw/ in the URL.
9. There you go, Now use that URL in your Tivimate. And Tivimate will update the playlist automatically once you open the app.
10. ![image](https://user-images.githubusercontent.com/90518979/136909762-9fed542f-21cb-4194-a71f-79e6aa016b01.png)


Now you don't need to touch anything, It updates the playlist on it's own everyday and you only need to Update the playlist in Tivimate.
All the steps above are to be done only for once. Please Star my repo if you've liked my work! :)

## FAQs

Q. Does playlist still work if I change Tata Sky Password?

A. No, It doesn't. Incase you changed your Tata Sky Password, You need to run this workflow again.

Q. My Workflow fails.

A. Make sure that you've gave necessary permissions while creation of the token.

## Explanation on how this works

This works purely on the basis of GitHub Workflow Actions, So a VERY BIG THANKS to GitHub.
I've created the script where Actions will automatically trigger the workflow everyday for 2:30 AM IST.

The tokens, GitHub email and ID are required because we are basically creating another repo and gists with this script using them.

## Credits

* [Gaurav Thakkar](https://github.com/ForceGT) for his [IPTV Repo](https://github.com/ForceGT/Tata-Sky-IPTV)
* GitHub for their GitHub Actions
