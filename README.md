## Easy endpoint performance tests

These are just samples of Drill yml files.

You'll need Drill to run these benchmark tests. Drill is a Rust-powered tool, so you can use either `cargo` to install it or use tools like Homebrew if you are not a power user :D

- Install `Drill`
- Add a `yml` file defining what you want to benchmark according to [the Drill doc](https://github.com/fcsonline/drill).
- Run the command below (or any other command)


Note: there are a couple of examples included in the repo.
This means that you can directly edit either `benchmark.yml` or `benchmark-staging.yml` to specify what you wanna drill :)

### Typical command

```sh
  drill --benchmark benchmark-staging.yml --stats
```

### Doc

[drill](https://github.com/fcsonline/drill)
