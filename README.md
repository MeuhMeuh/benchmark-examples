## Easy endpoint performance tests

- Add a `yml` file defining what you want to benchmark according to [the Drill doc](https://github.com/fcsonline/drill).


Note: there are a couple of examples included in the repo.
This means that you can directly edit either `benchmark.yml` or `benchmark-staging.yml` to specify what you wanna drill :)

### Typical command

```sh
  drill --benchmark benchmark-staging.yml --stats
```

### Doc

[drill](https://github.com/fcsonline/drill)
