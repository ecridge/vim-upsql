# upsql.vim

Quick-’n’-dirty Vim plugin that uppercases SQL keywords (according to
[PostgreSQL 9.6][ref]) as you type.

## Why?

- Capitalising keywords makes the code more readable, but typing in caps is
  a pain.

- The case change makes it easier to spot if you accidentally use a keyword as
  an identifier (’cause who remembers all ~800?).

## To do

- [ ] Don’t uppercase inside quotes.

## Installation

Using [Pathogen](https://github.com/tpope/vim-pathogen):

```bash
cd ~/.vim/bundle && \
git clone https://github.com/joecridge/vim-upsql.git
```

[ref]: https://www.postgresql.org/docs/9.6/static/sql-keywords-appendix.html
