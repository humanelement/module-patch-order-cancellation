# module-patch-order-cancellation

    composer require human-element/module-patch-order-cancellation

This module addresses some issues with order cancellation. Observers fire when the order is cancelled from the admin, but not when it is cancelled from the frontend, i.e. a failed checkout. This has the consequence of, for example, not resetting a gift card balance. For details, please see the [2017 HEI blog post](https://www.human-element.com/magento-2-bug-rewards-points-payment-decline/).
