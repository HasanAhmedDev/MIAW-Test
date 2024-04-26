<html>
  <body>
    <script type="text/javascript">
      function initEmbeddedMessaging() {
        try {
          embeddedservice_bootstrap.settings.language = "en_US"; // For example, enter 'en' or 'en-US'

          embeddedservice_bootstrap.init(
            "00D7i000000YF2V",
            "LCD_Messaging_Sandbox",
            "https://pitchbookdata--full.sandbox.my.site.com/ESWLCDMessagingSandbox1713810680638",
            {
              scrt2URL:
                "https://pitchbookdata--full.sandbox.my.salesforce-scrt.com",
            }
          );
        } catch (err) {
          console.error("Error loading Embedded Messaging: ", err);
        }
      }
    </script>
    <script
      type="text/javascript"
      src="https://pitchbookdata--full.sandbox.my.site.com/ESWLCDMessagingSandbox1713810680638/assets/js/bootstrap.min.js"
      onload="initEmbeddedMessaging()"
    ></script>
  </body>
</html>
