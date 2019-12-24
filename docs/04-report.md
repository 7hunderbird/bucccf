## report

Now that we've got a running Cloud Foundry we can run our report.

```
./script/report | sort
```

This will output what certificates the current Cloud Foundry is using, sorted by SHA256 fingerprint, Common Name, and `/path/ca`.

Requires:

* [yq](https://mikefarah.github.io/yq/)
* [jq](https://stedolan.github.io/jq/)

[Next](99-bucc-down.md)