# ie-unsupported
A simple landing page to tell IE users that they need to use a different browser

- Using W3.CSS

- Page size 14.8KB

- Load time 188ms

- Requests 4

I have this .html hosted on a subdomain of my site, and use the following head injection to identify IE browsers and send them to the subdomain:

```
 <!--[if IE] -->
<script>
    if (window.document.documentMode) {
        window.location.href = "WHEREVER YOU HOST THIS HTML.COM";
}
</script>
<!--[end IE]-->
```
