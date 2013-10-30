##Overview
wp-ChromeLogger is a simple WordPress mu-plugin which wraps Chrome Logger: 
https://github.com/ccampbell/chromephp for global usage.
It allows you to log variables, arrays and even Objects to the Chrome Console.

More information can be found here:
http://www.chromelogger.com


##Installation
1. Install the Chrome extension from: https://chrome.google.com/extensions/detail/noaneddfkdjfnfdakjjmocngnfkfehhd
2. Click the extension icon in the browser to enable it for the current tab's domain

3. Create the following folder if not already present:

    ```PHP
    /wp-content/mu-plugins
    ```
4. Run the following terminal command in the previous generated folder (or download and extract)

    ```
    git clone 
    ```

5. Copy "autoload-ChromeLogger.php" to ```/wp-content/mu-plugins```


##Usage 
After installing you can simply log data anywhere as the following :

```
    ChromePhp::log('Hello console!');
    ChromePhp::log($_SERVER);
    ChromePhp::warn('something went wrong!');
``` 

--------------

References:
http://codex.wordpress.org/Must_Use_Plugins


