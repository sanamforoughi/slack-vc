#Slack-VC
Slack-VC is a Slack integration to look up famous Venture Capital's portfolio list. It's built for startup enthusiasts! 😇
![Example](http://g.recordit.co/F1OKTHKVfu.gif)

## Coverage
Currently, the VCs supported and corresponding commands:

- [a16z](http://a16z.com/) (a16z)
- [Founders Fund](http://foundersfund.com/) (ff)
- [Google Ventures](http://www.gv.com/) (gv)
- [GreyLock Partners](http://www.greylock.com/) (greylock)
- [Khosla Ventures](http://www.khoslaventures.com/) (khosla)
- [Sequoia Capital](https://www.sequoiacap.com/) (sequoia)
- [KPCB](http://www.kpcb.com/) (kpcb)

## Integrate with your Slack

1. Go to one of your Slack channel.
2. Click the **Channel Settings**.
3. In the settings menu, click the **Add an app or integration**.
4. In the top menu bar, click **Manage**, then click the **Custom Integrations** on the left menu bar.
5. Click **Slash Commands**.
6. Click **Add Configuration**.

  - Command: /vc
  - URL: https://slack-vc.herokuapp.com/
  - Method: **POST**
  - In the Autocomplete help text section, check to allow autocomplete.
    - Description: VC's portfolio list, articles is in Slack now!
    - Usage hint: [VC name +  Space + Option]

7. All set!

## Usage
After adding Slack-VC integration to your team, within any channel of your team,
- To look up portfolio, in your input box, simply type **/vc [VC name + space + p]**
  - For example: **/vc a16z p**
