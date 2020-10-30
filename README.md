# nginx-index-awsl
nginx auto index template

```
location / {
    add_before_body /header.html;
    add_after_body /footer.html;
    charset utf-8;
    autoindex on;
    autoindex_exact_size on;
}
```
