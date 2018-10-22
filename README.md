# Scrape BGer headers
Ruby script to scrape the swiss supreme court decision's headers.

## Files

Two .rb files are included:

- `scrabe2md.rb` scrapes all decisions from year 134 (2008) to 144 (2018) and renders a .md file for each volume (I to IV) by year.
- `scrabe2jekyll.rb` does the same but outputs a [jekyll](https://jekyllrb.com) collection file.

## Requirements

1. Get ruby going on your system.
2. Install [Nokogiri](http://www.nokogiri.org/tutorials/installing_nokogiri.html).
3. For, `scrabe2jekyll.rb`, make sure you've got [jekyll](https://jekyllrb.com) installed to render the files correctly.
