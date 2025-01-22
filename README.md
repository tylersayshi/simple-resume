# Simple Resume Theme

This theme is meant to create a web based, simple resume, that you can print.

![Screenshot](https://raw.githubusercontent.com/tylersayshi/simple-resume/3495ff7d4351510595820d08a7f3b01733197e75/images/tn.png)

## Features

- Web based resume
- Printable
- Straightforward/simple design

## Install theme on your hugo site

```
hugo new site your-site-name # if you already have a site ignore this line and the next
cd your-site-name
cd themes
git clone https://github.com/tylersayshi/simple-resume.git
```

Once you have done this, you may use the `exampleSite` folder as an example for how to set your project up. The two main things to pay attention to is to first set this in your `config.toml` file:

```toml
theme = "simple-resume"
```

Then you will need to replicate the data used in the `exampleSite/data/content.yaml` file to fill in the fields for your resume.

## Print your Resume

You can print the page straight to a pdf or to paper if you wish. I have had best luck printing with the margins set to 'minimum', but you can set custom margins when printing if it looks off to you.

## Contributing

Please feel free to post issues or make pull requests at any time. I am always open to collaboration.
