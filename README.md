Welcome to jquery-multirecaptcha
================================

It's a project meant to hack one of the Google's Recaptcha system limit. Now it's possible to have multiple forms on one page and every of them has Recaptcha

Usage
-----

1. Include jQuery(tested on 1.8.3+) in the head section
2. Include jquery.multirecaptcha in the head section
3. Run jquery-multirecaptcha with

```javascript
    <script type="text/javascript">
        $(document).ready(function(){
            $("form").multirecaptcha({
                public_key: "YOUR_API_KEY",
                always_refresh: true
            });
        });
    </script>
```