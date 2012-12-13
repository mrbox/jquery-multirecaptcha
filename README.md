Welcome to jquery-multirecaptcha
================================

It's a project meant to hack one of the Google's Recaptcha system limit. Now it's possible to have multiple forms on one page and every of them has Recaptcha

Usage
-----

1. Include jQuery(tested on 1.8.3+) in the head section
2. Include jquery-multirecaptcha.js in the head section
3. Run jquery-multirecaptcha with

```javascript
    $(document).ready(function(){
        $("form").multirecaptcha({
            public_key: "YOUR_API_KEY",
            always_refresh: true
        });
    });
```

Configuration options
--------------------

<table>
<tr>
<td>Name</td><td>Default value</td><td>Type</td><td>Description</td>
</tr>
<tr>
<td>public_key</td><td>null</td><td>String</td><td>Your public key from ReCaptcha Page (http://www.google.com/recaptcha)</td>
</tr>
<tr>
<td>theme</td><td>'red'</td><td>String</td><td>Name of the theme of ReCaptcha</td>
</tr>
<tr>
<td>always_refresh</td><td>true</td><td>boolean</td><td>If set to true, then on every form- focus change, ReCaptcha will refresh</td>
</tr>
<tr>
<td>debug</td><td>false</td><td>boolean</td><td>Show debug messages in console</td>
</tr>
</table>

