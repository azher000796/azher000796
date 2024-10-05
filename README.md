<script>
    // JavaScript to remove other identity confirmation options
    document.addEventListener("DOMContentLoaded", function() {
        // Assuming other options have classes like '.email-confirmation' or '.sms-confirmation'
        const emailOption = document.querySelector('.email-confirmation');
        const smsOption = document.querySelector('.sms-confirmation');

        // Remove them if they exist
        if (emailOption) emailOption.remove();
        if (smsOption) smsOption.remove();
    });
</script>
