<!DOCTYPE html>
<html lang='en'>

<head>
    <meta charset='UTF-8'>
    <meta name='viewport' content='width=device-width, initial-scale=1.0, minimum-scale=1'>
    <title>Document</title>
</head>

<body>
        <div>
            Webpage
        </div>
        <div>
            <div id='chatBtn' style='display: none;'>
                Online
            </div>
    </div>

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
