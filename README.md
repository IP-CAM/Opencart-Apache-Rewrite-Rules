## OpenCart Apache Rewrite Rules

for OpenCart 2.3.X

Adding following:
```

RewriteRule ^cart/?$ index.php?route=checkout/cart [L]
RewriteRule ^checkout/?$ index.php?route=checkout/checkout [L]
RewriteRule ^contact/?$ index.php?route=information/contact [L] 
ReWriteRule  ^account/?$  index.php?route=account/account  [L]
ReWriteRule  ^account/edit/?$  index.php?route=account/edit  [L]
ReWriteRule  ^account/password/?$  index.php?route=account/password  [L]
ReWriteRule  ^account/address/?$  index.php?route=account/address  [L]
ReWriteRule  ^account/wishlist/?$  index.php?route=account/wishlist  [L]
ReWriteRule  ^account/order/?$  index.php?route=account/order  [L]
ReWriteRule  ^account/download/?$  index.php?route=account/download  [L]
ReWriteRule  ^account/reward/?$  index.php?route=account/reward  [L]
ReWriteRule  ^account/return/?$  index.php?route=account/return  [L]
ReWriteRule  ^account/transaction/?$  index.php?route=account/transaction  [L]
ReWriteRule  ^account/recurring/?$  index.php?route=account/recurring  [L]
ReWriteRule  ^account/newsletter/?$  index.php?route=account/newsletter  [L]
ReWriteRule  ^account/login/?$  index.php?route=account/login  [L]
ReWriteRule  ^account/logout/?$  index.php?route=account/logout  [L]Link
ReWriteRule  ^brands/?$  index.php?route=product/manufacturer  [L] 
ReWriteRule  ^special/?$  index.php?route=product/special  [L]
ReWriteRule  ^account/vouchers/?$  index.php?route=account/voucher  [L]

```
