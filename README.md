# TCY-FCS Consortium Resource Webpage — published build

The encrypted build of the consortium's resource site, served by GitHub Pages.

Nothing here is readable without the site password. `index.html` is a lock
page that carries the encrypted site; `f/` holds the encrypted files it links
to, under opaque names. `crypt.json` holds the key-derivation salt, which is
not secret.

**Do not edit anything in this repository by hand.** It is generated output,
rebuilt and replaced on every publish by `script/publish.sh` in the site's
source repository.
