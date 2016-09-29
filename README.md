# LaunchBox: Pre-Launch Campaign Template
![alt tag](http://i.imgur.com/K4sId2g.gif)

*Live demo available at https://derekparryslc.github.io/launchrock.*

#### What is LaunchBox?
**LaunchBox** is a free pre-launch campaign template that integrates [formspree.io](https://formspree.io) and a facebook share button. It is modeled after the old LaunchRock (www.launchrock.com), which was awesome. I waited around for something like it to resurface, but nothing ever did. So I made LaunchBox.

LaunchBox goes hand-in-hand with the [Lean Startup](https://en.wikipedia.org/wiki/Lean_startup) methodology of refraining from investing in something before you know there is sufficient demand for it. In a matter of minutes, you can create a new launchbox, share it on reddit and facebook, and start getting people in your inbox who are genuinely interested in your project. The facebook share button also makes it easy for people to share your idea, bringing in more followers.

I've used LaunchBox twice (see the [examples below](https://github.com/DerekParrySLC/launchbox/blob/master/README.md#2-how-to-set-up-your-launchbox)) and both times it worked great. The first time (for an app idea) it brought in over one hundred people. The second time (for my friends self-published book) it brought in about sixty people. Not anything huge, but for a limited amount of work it was a great jumpstart for getting an audience right out of the gate and making each project a success.

Below are **_super basic instructions_** for how you can easily copy this repo and setup your own launchbox, hosted right here on GitHub.

*Please note: I opted to not to use certain tools (such as a templating library) so that LaunchBox would remain beginner friendly. If you have any suggestions on how to improve, I would love to hear them. Please either submit a pull request and send me a message.*

##Table of Contents
1. [Two examples of LaunchBox in action](https://github.com/DerekParrySLC/launchbox/blob/master/README.md#1-two-examples-of-launchbox-in-action)
2. [How to set up your launchbox](https://github.com/DerekParrySLC/launchbox#2-how-to-set-up-your-launchbox)
3. [How to further customize your launchbox](https://github.com/DerekParrySLC/launchbox#3-how-to-further-customize-your-launchbox)
4. [How to market your launchbox and build a following](https://github.com/DerekParrySLC/launchbox#4-how-to-market-your-launchbox-and-build-a-following)
5. [FAQ/Contact/Troubleshooting](https://github.com/DerekParrySLC/launchbox#5-faqcontacttroublshooting)

## 1. Two examples of LaunchBox in action
**[BirthCurrent](https://www.birthcurrent.com)** - Social news app for the birth community. Generated a following of over one hundred people after posting in several online facebook groups. Currently in development, though possibly will not be completed due to other reasons.

**[Magic in Every Corner](http://www.magicineverycorner.com)** - Collection of short stories by my friend Jonathan Griffin. He shared this "launchbox" on his facebook page and got about sixty people to sign up. Not a lot, but all things considered it was a great turnout.

## 2. How to set up your launchbox

**Step 1. Log in to Github.** Create a GitHub account if you don't already have one. If you do, log in.

**Step 2. Fork this repo.** Click on the "fork" button at the type right of this page.

**Step 3. Open the `index.html` file.** Navigate to the forked repo in your account. Click on the `index.html` page. Next, click on the pencil icon on the type right to edit the file.

**Step 4. Edit `og:title`.** On line 8, change `LaunchBox: Pre-Launch Campaign Template` to the title that you want when people share it on facebook. (We will edit the `og:image` tag later.)

**Step 5. Edit the title of the website.** On line 12, change `LaunchBox` to the title of your project.

**Step 6. Edit the text of the launchbox.** On lines 32-35, change the text from the LaunchBox text to the tex that you want.

**Step 7. Change the target email address.** On line 36, change `rexburgcandyvend@gmail.com` to your email.

**Step 8. Change email placeholder.** On line 38, change `fake@email.com` to `your@email.com`.

**Step 9. Publish your page.** Click on Settings in the top right. Scroll down to the fourth box titled "GitHub Pages." In the dropdown box, select "master branch" and click save. The page should reload. Scroll back down to the "GitHub Pages" box. Up top in green it should give you the URL for your site. Click on the URL.

**Step 10. Take a screenshot of your launchbox.** Using the snipping tool (Windows) or command-shift-4 (Mac) take a screen shot of the homepage of your launchbox URL. **Save it as `share-image.jpg` somewhere where you can find it.** MAKE SURE YOUR IMAGE IS SAVED AS A JPG, NOT PNG. If it is not a jpg, you will need to convert it. Google how to do this if you are unsure.

**Step 11. Replace `share-image.jpg` with your image.** Navigate back to list of files and open the `share.html` file. Click on the trashcan in the top right to delete it, then commit the delete. Now, naviagte back to the file list. In the top right, click on "Upload files." Upload your `share-image.jpg` file.

**Step 12. Create your facebook share button.** In a different tab, go to https://developers.facebook.com/docs/plugins/share-button. Paste the URL to your launchbox home page in the "URL to share" field. It should look like `https://[yourUserName].github.io/launchbox/`. Choose your button layout and size. **MAKE SURE THE "MOBILE IFRAME" CHECKBOX IS _NOT_ CHECKED.** Click "get code." Rather than the JavaScript SDK, we're going to go with the iFrame. So, up above, select "IFRAME." Copy pase the code. Copy the entire iFrame code onto you clipboard by selecting the code and hitting ctrl-c.

**Step 13. Paste your iframe into `share.html`.** Go back to your launchbox's files and open up `share.html`. On line 30, replace the current iFrame code with your new iFrame that you copied by selecting it and pressing ctrl-v.

**Step 14. Verify your email with [formspree.io](https://formspree.io).** Open up the homepage of the URL for your launchbox. Again, it should be `https://[yourUserName].github.io/launchbox/`. Once there, type in any email address, fake or real, into the sign-up form. This should now take to you a formspree page saying that you need to verify you email. Go do that.

**Step 15. You're done!** Go back to the home page and try submitting another email. The new "subscriber" should appear in your inbox. (It may take a minute or two). Congratulations! You are now ready to go out into the world with your new launchbox and build a following. Share it on reddit; share it on facebook. Don't be spammy, be real and provide genuine value, and you will begin to build a following. See below for more customization options (custom background, custom domain, custom colors, custom fonts, etc.) as well as additional tips on how to share your launchbox and build a following.

## 3. How to further customize your launchbox

If there is enough interest in this repo, I'll add here the following additional instructions
1. How to source and change the background image
2. How to get and apply a custom domain
3. How to change the color scheme
4. How to find and integrate custom fonts

Anything else I should add? Let me know by submitting an issue and I'll try to include it. Also, if you have any good ideas you would like to implement yourself, please submit a pull request.

## 4. How to market your launchbox and build a following

Same as above: If there is sufficient interest in this repo, I'll add here some tricks and tips on how to share your launchbox and build a following. Please show your support by starring and forking this repo up above.

## 5. FAQ/Contact/Troublshooting

I'll post frequently asked questions here as they come in.

If you would like to contact me, please submit an issue or a pull request.

Having trouble with you launchbox? Please paste your code into a [gist](https://gist.github.com/) and submit the link to your gist as an issue.




