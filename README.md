# LaunchBox: Pre-Launch Campaign Template
![alt tag](http://i.imgur.com/K4sId2g.gif)

*Demo at https://derekparryslc.github.io/launchbox*

#### What is LaunchBox?
**LaunchBox** is a free pre-launch campaign template that integrates [formspree.io](https://formspree.io) and a facebook share button. It is modeled after the old LaunchRock (www.launchrock.com), which was awesome. I waited around for something like it to resurface, but nothing ever did. So I made LaunchBox.

LaunchBox goes hand-in-hand with the [Lean Startup](https://en.wikipedia.org/wiki/Lean_startup) methodology of refraining from investing in something before you know there is sufficient demand for it. In a matter of minutes, you can create a new launchbox, share it on reddit and facebook, and start getting email addresses in your inbox of people who are genuinely interested in your project. The facebook share button also makes it easy for people to share your idea, bringing in more followers.

##Table of Contents
1. [Two examples of LaunchBox in action](https://github.com/DerekParrySLC/launchbox/blob/master/README.md#1-two-examples-of-launchbox-in-action)
2. [How to set up your launchbox](https://github.com/DerekParrySLC/launchbox#2-how-to-set-up-your-launchbox)
3. [How to further customize your launchbox](https://github.com/DerekParrySLC/launchbox#3-how-to-further-customize-your-launchbox)
4. [How to market your launchbox and build a following](https://github.com/DerekParrySLC/launchbox#4-how-to-market-your-launchbox-and-build-a-following)
5. [FAQ/Contact/Troubleshooting](https://github.com/DerekParrySLC/launchbox#5-faqcontacttroublshooting)

## 1. Two examples of LaunchBox in action
**[BirthCurrent](https://www.birthcurrent.com)** - Social news app for the birth community. Generated a following of over one hundred people after posting in several online facebook groups. Currently in development, though possibly will not be completed due to time constraints. (Let me know if you're interested in developing a simple social news app.)

**[Magic in Every Corner](http://www.magicineverycorner.com)** - Collection of short stories by my friend Jonathan Griffin. He shared this "launchbox" on his facebook page and got about sixty people to sign up. Not a massive amount, but all things considered it was a great turnout.

## 2. How to set up your launchbox

**Step 1. Log in to Github.** Create a GitHub account if you don't already have one. If you do, log in.

**Step 2. Fork this repo.** Click on the "fork" button at the top right of this page.

**Step 3. Open the `index.html` file.** Navigate to the forked repo in your account. Click on the `index.html` page. Next, click on the pencil icon on the type right to edit the file.

**Step 4. Edit `og:title`.** On line 8, change `LaunchBox: Pre-Launch Campaign Template` to the title that you want when people share it on facebook. (We will take care of the `og:image` tag later, in Step 11.)

**Step 5. Edit the title of the website.** On line 12, change `LaunchBox` to the title of your project.

**Step 6. Edit the text of your launchbox.** On lines 32-35, change the text of the launchbox text to the tex that you want.

**Step 7. Change the target email address.** On line 36, change `rexburgcandyvend@gmail.com` to your email.

**Step 8. Change email placeholder, commit your changes.** On line 38, change `fake@email.com` to `your@email.com`. Scroll down to the bottom and commit your changes.

**Step 9. Publish your page.** Click on Settings in the top right. Scroll down to the fourth box titled "GitHub Pages." In the dropdown box, select "Master Branch" and click save. The page should reload. Scroll back down to the "GitHub Pages" box. Up top in green it should give you the URL for your site. Click on the URL.

**Step 10. Take a screenshot of your launchbox's homepage.** Using the snipping tool (Windows) or command-shift-4 (Mac) take a screen shot of the homepage of your launchbox URL. **Save it as `share-image.jpg` somewhere where you can find it.** MAKE SURE YOUR IMAGE IS SAVED AS A JPG, NOT PNG. If it is not a jpg, you will need to convert it. If you are unsure how to do this, google it.

**Step 11. Replace `share-image.jpg` with your image.** Navigate back to list of files and open the `share.html` file. Click on the trashcan in the top right to delete it, then scroll down and commit the delete. Now, naviagte back to the file list. In the top right, click on "Upload files." Upload the `share-image.jpg` file that you juts created and saved to your computer.

**Step 12. Create your facebook share button.** In a different tab, go to https://developers.facebook.com/docs/plugins/share-button. In the "URL to share" field, paste the URL to your launchbox's home page. It should look like `https://[yourUserName].github.io/launchbox/`. Choose your button layout and size. **MAKE SURE THE "MOBILE IFRAME" CHECKBOX IS _NOT_ CHECKED.** Click "get code." Rather than the JavaScript SDK, we're going to go with the iFrame. So, up above, select "IFRAME." Copy the entire iFrame code onto your clipboard by selecting the code and hitting ctrl-c.

**Step 13. Paste your iframe into `share.html`.** Go back to your launchbox's files and open up `share.html`. On line 30, replace the current iFrame code with your new iFrame by selecting the current iFrame code and pressing ctrl-v.

**Step 14. Verify your email address with [formspree.io](https://formspree.io).** Open up the homepage of the URL for your launchbox. (Again, it should be `https://[yourUserName].github.io/launchbox/`.) Once there, type in any email address, fake or real, into the sign-up form. Press enter. This should now take to you a formspree page saying that you need to verify your email address. Go do that.

**Step 15. You're done!** Go back to the home page and try submitting another email address. The new "subscriber" should appear in your inbox. (It may take a minute or two). Congratulations! You are now ready to go out into the world with your new launchbox and build a following. Share it on reddit; share it on facebook. Don't be spammy, be real and provide genuine value, and you will begin to build a following. See below for more customization options (custom background, custom domain, custom colors, custom fonts, etc.) as well as additional tips on how to share your launchbox and build a following.

## 3. How to further customize your launchbox

If this repo generates enough interest, I'll add here the following additional instructions:

1. How to source and change the background image
2. How to get and apply a custom domain
3. How to change the color scheme
4. How to find and integrate custom fonts

**Anything else you would like me to add?** Let me know by submitting an issue and I'll try to include it. Also, if you have any features that you would like to implement yourself, please submit a pull request.

## 4. How to market your launchbox and build a following

Same as above: If there is sufficient interest in this repo, I'll add here some tricks and tips on how to share your launchbox and build a following. Please remember to star and fork this repo up above.

## 5. FAQ/Contact/Troublshooting

I'll post frequently asked questions here as they come in.

If you would like to contact me, please submit an issue or a pull request.

Having trouble with you launchbox? Please paste your code into a [gist](https://gist.github.com/) and submit the link to your gist as an issue.
