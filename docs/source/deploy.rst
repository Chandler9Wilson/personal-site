Deploying the Project
=====================

Where things are found
----------------------

* Most Static Files/Projects can be found under ``/var/www/``
* Dealer Portal is normally under the user who deployed it e.g. ``/home/chandler/dealer-portal``
* Per Site nginx config is under ``/etc/nginx/sites-available``

Updating Content
----------------

From the project root that you would like to update

1. Run ``$ git pull``
2. ``$ sudo systemctl restart nginx``

Guides Used
-----------

* How to `set up Let's Encrypt`_
* How to `set up NGINX server blocks`_

.. _`set up Let's Encrypt`: https://certbot.eff.org/lets-encrypt/ubuntuxenial-nginx
.. _`set up NGINX server blocks`: https://www.digitalocean.com/community/tutorials/how-to-set-up-nginx-server-blocks-virtual-hosts-on-ubuntu-16-04