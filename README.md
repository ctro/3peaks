# 3Peaks Massage public site

This is static HTML, yay.

## Development

```
python -m SimpleHTTPServer 8080
open localhost:8080
```

## Production

Site is hosted in an s3 bucket.
Deploy: `aws s3 sync . s3://3peaksmassage`


## TODO

- [ ] Simple SPA Styles
- [ ] Text / logo replacement
