# Tamperish for Safari


_Tamperish_ is developed to be an easy-to-use user styles & scripts injection tool. 💉 It allows you to tamper with web pages using CSS & JavaScript snippets pretty much any way possible. 👷‍♂️

![Main window of Tamperish](https://i.imgur.com/QOWVhAW.png)

_Tamperish_ attempts to recover most of the customisation abilities formerly provided by _Tampermonkey_ and _Stylish_ extensions, but using a simpler, more strict injection hierarchy. 👾

## Customisation examples

Some examples of how can Tamperish be used for customisation are now available on GitHub, too!

https://github.com/username0x0a/Tamperish-tweaks

Feel free to use these as inspiration and eventually push your own contributions, too! 🙏

## How to use

- Open the app
- Pick a `Tampers` folder where all customisation files will be stored 🗂
- Add some _Tamper_ files (either _CSS_ styles or _JavaScript_ scripts) according to the hierarchy described below: 🖍 ![Folder structure](https://i.imgur.com/eUSINxe.png)
	- `www.google.com` folder will be applied on _Google Search_ page
	- `com` folder contents will be applied on all `com` domains
	- Tamper files placed directly to the `Tampers` folder will be applied everywhere
- Enable the extension in _Safari_ preferences – can be done by clicking the **On/Off** button in the app
- Refresh the desired web page & profit. 👍

![Page style snippet example](https://i.imgur.com/5DJSXDD.png)
