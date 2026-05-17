# PlainCam Public Site

Public product, support, and privacy pages for PlainCam.

- Home: `/`
- Privacy Policy: `/privacy/`
- Support: `/support/`

## Local Preview

Install dependencies inside the repository:

```sh
/opt/homebrew/opt/ruby/bin/bundle config set path vendor/bundle
https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890 /opt/homebrew/opt/ruby/bin/bundle install
```

Run Jekyll locally:

```sh
/opt/homebrew/opt/ruby/bin/bundle exec jekyll serve --livereload
```

Open:

```text
http://127.0.0.1:4000/plaincam-site/
```
