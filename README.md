# RubyDocVersion for Safari

Safari Extension to automatically redirect to the correct version at ruby-doc.org

### Why?

I was constantly finding myself looking at old ruby doc versions since Google results often returns them in the wrong order:

<img src='https://github.com/mcfadden/RubyDocVersion/blob/master/screenshots/search-results.png?raw=true' width="300" alt="Google confusesd me" />

## Usage

#### Installation
[Download](https://github.com/mcfadden/RubyDocVersion/blob/master/RubyDocVersion.safariextz?raw=true) and open.

You'll need to "trust" the extension.

#### Settings

Safari menu > Preferences > Extensions > RubyDocVersion

Select the Version of Ruby you use.

<img src='https://github.com/mcfadden/RubyDocVersion/blob/master/screenshots/settings.png?raw=true' width="300" alt="Select the Ruby Version you use" />

Now when you visit old docs (ex: [http://ruby-doc.org/core-1.9.3/](http://ruby-doc.org/core-1.9.3/)) you are automatically redirected to the version you selected.

## Notes

This requires full webpage permission so it can rewrite the URL. The source is really simple, so if that makes you nervous take a look.
