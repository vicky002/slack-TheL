# slack-TheL
--------------
The Genious L, now in slack to answer all your Queries! :sunglasses:
![img](https://github.com/vicky002/slack-TheL/raw/master/theL.gif)



## Usage

from any slack channel just type `thel [your question]`. The Question will be shown on the same channel visible to you.



## Integrate it with your team

**As the Wolframalpha API allows only 2000 API calls in a month. This can not be used directly. **

**I wrote a tutorial on How to create this bot. Read [here](http://eulercoder.me/posts/How-to-create-Slack-Bot-using-wolframalpha-API/)**


1. Go to your channel
2. Click on **Configure Integrations**.
3. Scroll all the way down to **DIY Integrations & Customizations section**.
4. Click on **Add** next to **Slash Commands**.
   - Command: `thel`
   - URL: `https://slack-thel.herokuapp.com/thel`
   - method: `POST`
   - For the **Autocomplete help text**, check to show the command in autocomplete list.
    - Description: `The Genius L, is now in slack to answer all your queries.`
    - Usage Hint: `[search query]`
  - Descriptiive Level: `Search Query`



## Developing

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

You will need to set the `wol_id` environment variable in `config.py` file in your heroku app in order for this to work. You can read more about it [clicking here](https://devcenter.heroku.com/articles/config-vars#setting-up-config-vars-for-a-deployed-application)



## Contributing
- Please use the [issue tracker](https://github.com/vicky002/slack-TheL/issues) to report any bugs or file feature requests.

## LICENCE

[MIT LICENSE](https://github.com/vicky002/slack-TheL/blob/master/LICENSE) (c) Vikesh Tiwari
