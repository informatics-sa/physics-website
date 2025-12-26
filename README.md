# Saudi Physics Team website

Total Saudi medals as of 2025:
- [NBPhO](https://x.com/mawhiba/status/1915692296286126589): 4/5 participations
- [APhO](https://x.com/mawhiba/status/1919021998455345155): 4/16 participations
- [IPhO](https://x.com/mawhiba/status/1945765011223155139): 12/12 participations
- [EuPhO](https://x.com/mawhiba/status/1812747700984496249) / [Another source](https://x.com/moe_gov_sa/status/1814390806838685781): 7/7 participations
- [GPhO](https://x.com/mawhiba/status/1845728842305949942): 2/5 participations

## Local Build
### Prerequisites
You need:
- [Python Interpreter](https://python.org)
- [Ruby Interpreter](https://www.ruby-lang.org)
- Install Ruby dependencies using [Bundler](https://bundler.io):
```sh
bundle install
```

<details>
    <summary>How does it work?</summary>
    `bundle` is a package manager, `Gemfile` contains the packages list.
    Jekyll latest version is 4.4.1, but the current version used in Github pages is 
</details>

### Building & Local Serving
```sh
python build.py && bundle exec jekyll serve -s ./root
```

## License
This project is licensed under the GNU General Public License v3.0.

Check [LICENSE](https://github.com/informatics-sa/informatics-sa.github.io/blob/main/LICENSE)
