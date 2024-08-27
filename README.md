As of 8/27/24, this is being used on WordPress pages to allow React apps in iframes to communicate with the parent window. This allows the app in the iframe to get URL information, navigate the user to other pages, etc.

It interacts with IFrameHelperProvider. Copy the iframe and the script tag into a code block in Oxygen. Edit the "src" variable to easily set the URL the iframe will be pointed at. Then any components rendered in the iframe that are using the iframe context will have these features enabled.
