# March 2025

- fixed deprecated warnings related to math and sass 3.0: divisions etc.
- fixed deprecated warnings about clearfix in mixins
- converted from @import to @use to get rid of deprecation errors around that

- got rid of share button on post
- got rid of twitter and added mastodon and bluesky
- changed blockquote styling
- changed footnote number styling
- hid the "intro" section on the post layout. 

- had a problem with the footer overlapping the main content: changed .push in _styles to hard coded 300px which seems to fix it?