<html>
    <body>
        <script type='text/javascript'>
        function initEmbeddedMessaging() {
            try {
                embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
                embeddedservice_bootstrap.init(
                    '00D5E000000A9Mr',
                    'test',
                    'https://tti-fc--miaw.sandbox.my.site.com/ESWtest1689794181408',
                    {
                        scrt2URL: 'https://tti-fc--miaw.sandbox.my.salesforce-scrt.com'
                    }
                );
            } catch (err) {
                console.error('Error loading Embedded Messaging: ', err);
            }
        };
    </script>
    <script type='text/javascript' src='https://tti-fc--miaw.sandbox.my.site.com/ESWtest1689794181408/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
    </body>
</html>
