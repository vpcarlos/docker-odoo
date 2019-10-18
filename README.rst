==================
docker-odoo-postgesql
==================

.. image:: https://img.shields.io/static/v1.svg?label=license&message=LGPL%20v3&color=blue
   :target: https://www.gnu.org/licenses/lgpl-3.0
   :alt: License: LGPL v3

.. image:: https://img.shields.io/static/v1.svg?label=maturity&message=Beta&color=yellow
   :target: https://aselcis.com
   :alt: Maturity: Beta

Installation
============

1. Clone this repository

2. Replace default values with your own data:

    - docker-compose.yml ->  POSTGRES_PASSWORD, PGPASS, VIRTUAL_HOST,LETSENCRYPT_EMAIL, LETSENCRYPT_HOST
    - conf/odoo.conf -> admin_passwd, db_password
    
3. Run:

.. code:: console

        docker-compose up -d
 

Credits
=======

Contributors
------------

* Carlos Valdivia <vpcarlos97@gmail.com>

Maintainer
----------

* Carlos Valdivia <vpcarlos97@gmail.com>


