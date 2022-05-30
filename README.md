# ie-unsupported
A simple landing page to tell IE users that they need to use a different browser

- Using W3.CSS

- Page size 15.6KB

- Load time 192ms

- Requests 5

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
