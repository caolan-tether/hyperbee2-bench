# Hyperbee benchmarks

To run the benchmarks:

```
./run.js PATH_TO_HYPERBEE2_CHECKOUT
```

This will write the results to a JSON file in `www/results`.

Results can be viewed and compared between recent runs by serving up the
`www` directory:

```
python3 -m http.server -d www
```

You can run the latest benchmarks against other compatible hyperbee versions
by checking out different commits / tags in your hyperbee checkout directory
and running the benchmark script again. Recent runs will automatically appear
in the web UI on refresh.
