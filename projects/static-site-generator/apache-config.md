# apache config for this wiki

* Remove the [html extension](https://gist.github.com/davidvandenbor/f5a2c18c472ceb68d0dd) when serving files, because it's way cooler
* Use [certbot](https://certbot.eff.org/) for ssl — seriously, it's so easy.
    * Did you know that .dev domains _must_ use https?  Thankfully, it only takes an extra 30 seconds to set up with certbot!
* Use `mod_autoindex`:
    * `IndexOptions FancyIndexing SuppressHTMLPreamble XHTML IconsAreLinks FoldersFirst SuppressDescription`
