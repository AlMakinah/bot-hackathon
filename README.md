# AlMakinah bot hackathon

## Installation

### Part 1: *Cloning and Deploying your Bot*

- [ ] Clone this repo `git clone https://github.com/AlMakinah/bot-hackathon.git`
- [ ] Make sure you have `nodejs` and `npm` installed
- [ ] `cd` into your directory and `npm install`
- [ ] If you don't have account already, [signup on heroku](http://www.heroku.com)
- [ ] Download the [heroku toolbelt](https://toolbelt.heroku.com)
- [ ] Create an app on *heroku*
- [ ] Go to the deploy tab under your *heroku* app and get your deploy link `git remote add heroku <YOUR-DEPLOY-LINK-HERE>`
- [ ] Push your code to heroku `git push heroku master`
- [ ] Go to your app URL in the browser, you should see ***Hello world, I am a chat bot'***

### Part 2: *Connecting your Bot with Facebook*
- [ ] [Create a Facebook page if you don't have one already](https://www.facebook.com/pages/create) 
- [ ] Sign up https://developers.facebook.com/products/messenger
- [ ] Creating Facebook App for Messenger 
- [ ] Go to *My Apps*
- [ ] Click on "Add a New App"
- [ ] Add a *"Display Name"*, *"Contact Email"* and choose a category for your app
- [ ] Add a *"Messenger"* App
- [ ] Under *"Token Generator"* select your page and generate a token.
- [ ] Add the newly generated token in your code and push updates to heroku
- [ ] Setup a webhook, add your heroku app URL under *"Callback URL"* and your generated token under *"Verify Token"*
- [ ] if webhook is successful then you have connected your bot to Facebook!

### Part 3: *Test it*
- [ ] Go to your Bot's corresponding Facebook page and send your Bot a Message
- [ ] Sending anything will have it echo it back to you
- [ ] Sending "hi" will show you a catalog of interactive links with predefined answers


## Resources
- Facebook bots doc [https://developers.facebook.com/docs/messenger-platform](https://developers.facebook.com/docs/messenger-platform)
- Give your bot natural language [https://wit.ai/](https://wit.ai/)
- [https://howdy.ai/botkit/](https://howdy.ai/botkit/)
- [https://api.ai/](https://api.ai/)
- [https://textit.in/](https://textit.in/)
- [https://www.motion.ai/](https://www.motion.ai/)
- [https://chatfuel.com/](https://chatfuel.com/)