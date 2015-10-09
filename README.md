# Slacktivity

Do you want to know **right away** when your users do something **really important**? Slacktivity is a lightweight analytics library that allows you to send crucial user activity directly to your team's Slack. It's especially great for early-stage startups to know exactly what their early users are doing.

![demo](http://i.imgur.com/IOBUuja.gif)

# Why use Slacktivity?

Slacktivity has a different use case than traditional analytics platforms such as [Google Analytics](http://www.google.com/analytics/) and [Mixpanel](https://mixpanel.com). These platforms are fantastic for gathering tons of data on users and giving a clean interface to later interpret user behavior. Slacktivity, on the other hand, shines when there are *special* and *relatively rare* user events that you wanted to be notified of *right away*.

Some examples of when Slacktivity would be useful are:

* You're an early-stage startup with only a few users, and you want to be notified any time a user logs in.
* You're a SaaS company that just released a new, special feature to a small set of customers, and you want to know exactly when your customers use the new feature, and how they're using it.
* You have a crucial feature that should never break, but you want to be notified *immediately* if it does.

## Installation

```
bower install slacktivity
```
or

```Linux
npm install slacktivity
```

or 

Copy `slacktivity.js` into your project and add `<script src="slacktivity.js">` to your HTML header.

## Configuration

If you haven’t already, [set up an incoming Webhook in the integrations section of your Slack dashboard](https://slack.com/services/new/incoming-webhook).

In the config section at the top of `slacktivity.js`, add your own `webhook_url`. You also have the option to add a custom `title`, `icon_url`, or `text` in the config.

## Usage

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/MightySignal/slacktivity. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.


## License

The project is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

## Blog Post about Slacktivity

<Innsert blog post URL>

