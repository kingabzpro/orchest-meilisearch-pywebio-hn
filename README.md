# Orchest + Meilisearch + PyWebIO + HN

Search HN user comments through a PyWebIO interface backed by a Meilisearch DB

![Fetch HN and load into Meili pipeline](https://pviz.orchest.io/?pipeline=https://github.com/ricklamers/orchest-meilisearch-pywebio-hn/blob/master/load_and_search.orchest)

Import `https://github.com/ricklamers/orchest-meilisearch-pywebio-hn` to your Orchest instance to try it out.

On `Fetch data` you can configure:

```
{
  "all_pages": false,
  "proxy_enabled": true,
  "usernames": [
    "ricklamers"
  ]
}
```

On `Load into Meili` you can configure:
```
{
  "clear_db": true
}
```

<center><a href="https://www.tella.tv/video/ckxgcilet007w09ia0kei2z0z/view"><img width="634" alt="image" src="https://user-images.githubusercontent.com/1309307/146969144-77cf54e9-8a9c-4d02-9f95-c49bb1d10eb0.png"></a></center>
