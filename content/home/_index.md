+++
title = "Home page sections"
#
# Every .md file in this folder becomes a block on the front page, below the
# jumbotron, ordered by its `weight` (low numbers first).
#
# These pages are building blocks, not pages in their own right, so the
# cascade below stops Hugo giving them their own URLs.
#
[build]
  render = 'never'
  list = 'never'

[cascade]
  [cascade.build]
    render = 'never'
    list = 'local'
+++
