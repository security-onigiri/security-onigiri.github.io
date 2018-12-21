# security-onigiri

This blog is powered by [jekyll](http://jekyllrb.com/)

## Get started

```bash
gem install jekyll bundler
git clone https://github.com/security-onigiri/security-onigiri
cd security-onigiri
bundle install
bundle exec jekyll serve
```

Now browse to http://localhost:4000

## Writing a post

Access admin panel on http://localhost:4000/admin

Switch to `Posts` section and clink on `New post` button

Enter your post name on `Title`

### Metadata

press "New metadata field" to add a column in post header

- Add `your_name` into `author` field
- Add `original-link` into `source-url` field

## Deploy

Commit your change, or open a pull request to this repo.

Then execute `deploy.sh`.

See your changes on [https://security-onigiri.github.io/](https://security-onigiri.github.io/).

```bash
./deploy.sh
```

