# bitfinex-api-php
Bitfinex PHP API - Access all features of https://www.bitfinex.com trading platform

Get API keys from https://www.bitfinex.com/account/api

## Usage Example
    <?php
    include_once('Bitfinex.php');
    
    $api_key = 'xxxxxxxxxx';
    $api_secret = 'yyyyyyyyyy';
    $bfx = new Bitfinex($api_key, $api_secret);
    
    var_dump($bfx->get_symbols());
    ?>

## Support me
Bitcoin donations are welcome at [1x1UnfVJu7cprs3E2jjQ9WRcdDi5KJxAU](https://blockchain.info/address/1x1UnfVJu7cprs3E2jjQ9WRcdDi5KJxAU). Thank you!
