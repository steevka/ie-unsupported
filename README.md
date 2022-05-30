# ie-unsupported
A simple landing page to tell IE users that they need to use a different browser.

Using W3.CSS

Page size 15.6KB

I am using the following to identify IE browsers:

'''
 <!--[if IE] -->
<script>
    if (window.document.documentMode) {
        window.location.href = "WHEREVER YOU HOST THIS HTML.COM";
}
</script>
<!--[end IE]-->
'''