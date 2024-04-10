# myactions
Git actions.
#### Start the Server
- `cd /usr/local/var/homebrew/linked/elasticsearch-full/bin`
- `./elasticsearch`
To start ES from GUI, follow: https://opensource.com/article/19/7/installing-elasticsearch-macos

#### Test ES Set-up
- `curl -XGET http://localhost:9200`
Expected Response (Similar):
```
{
    "name": "PP-C02Z66CALVCG.local",
    "cluster_name": "elasticsearch_adesh.nalpet",
    "cluster_uuid": "E_543bFmSUqO7dXwzjE1WQ",
    "version": {
        "number": "7.8.1",
        "build_flavor": "default",
        "build_type": "tar",
        "build_hash": "b5ca9c58fb664ca8bf9e4057fc229b3396bf3a89",
        "build_date": "2020-07-21T16:40:44.668009Z",
        "build_snapshot": false,
        "lucene_version": "8.5.1",
        "minimum_wire_compatibility_version": "6.8.0",
        "minimum_index_compatibility_version": "6.0.0-beta1"
    },
    "tagline": "You Know, for Search"
}
```

#### Installation Redis (MacOS)
- `brew install redis`
- `brew services start redis` or `redis-server /usr/local/etc/redis.conf`
- `pip install django-redis`

#### Test Redis Set-up
- `redis-cli ping`
