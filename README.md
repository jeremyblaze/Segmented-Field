# Segmented Input

A jQuery powered segmented input field creator. Perfect for verification codes, pins etc


**Example usage...**

```
<input type="text" class="pin" maxlength="5" />

<script src="https://code.jquery.com/jquery-2.2.4.min.js" integrity="sha256-BbhdlvQf/xTY9gja0Dq3HiwQF8LaCRTXxZKRutelT44=" crossorigin="anonymous"></script>
<script type="text/javascript" src="jquery.segmentedInput.js"></script>
<script type="text/javascript">
    
    $(document).ready(function(){
        $('.pin').segmentedInput({
            // options
            autoSubmit: true
        });
    });
    
</script>
```

**Notes...**
- You MUST set the `maxlength` parameter otherwise the plugin won't know how many cells to create
- Your forms should work as normal - data will be populated into the .pin field automatically
- Paste works exactly as you'd expect (unlike many similar plugins)
- This is a jQuery-only plugin. No CSS is used – you'll need to create your own