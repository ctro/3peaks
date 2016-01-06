# 3Peaks Massage public site

This is static HTML, yay.

## Development

Run a simple webserver : `python -m SimpleHTTPServer 8080`

## Production

Site is hosted in an s3 bucket

### Deployment

`aws s3 sync . s3://3peaksmassage`
