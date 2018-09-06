# transaction-philosophy

Install [Hugo](https://gohugo.io/):

```
brew install hugo
```

Clone the repository:

```
git clone https://github.com/brandur/transaction-philosophy.git
cd transaction-philosophy/
```

For development, open a daemon that will serve from memory
(navigate to [https://localhost:1313]):

```
hugo server -D
```

Or generate the static site to `public/`:

```
hugo
```

Or for production:

```
hugo --config config.toml,config.prod.toml
```
