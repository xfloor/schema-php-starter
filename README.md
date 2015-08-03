# Schema Starter Template (PHP)

This template will help you get started building ecommerce functionality with Schema. Use it as a learning tool, the basis for a custom application, or take the pieces you need into an another project.

For more information on the Schema API, visit https://schema.io/docs.

## Setup

1) Upload the source to any basic PHP-enabled directory.

- Make the `cache` folder writable by the web server
- If you're running Apache, the included `.htaccess` can be used for clean URLs

2) Edit config.php with your Schema API credentials

```php
<?php // config.php

$config['client_id'] = 'client-id';

$config['client_key'] = 'secret-key';
```

That's it! Visit the home page and complete the setup steps provided (if applicable).

If you have trouble getting this far or just want to celebrate your first steps, join the community at https://slack.schema.io.

## Structure

```
cache/
lib/
account.php
blog.php
cart.php
category.php
checkout.php
checkout-billing.php
checkout-shipping.php
checkout-subscribe.php
config.php
footer.php
header.php
index.php
login.php
logout.php
page.php
product.php
receipt.php
subscription.php
```

## License

MIT
