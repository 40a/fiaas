.. Fiaas.co documentation master file, created by
   sphinx-quickstart on Sun Mar  8 09:18:34 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Fiaas.co's documentation!
====================================

Contents:

.. toctree::
   :maxdepth: 2

   intro
   general
   users
   virtualhost
   {% if varnish_required == True %}varnish{% endif %}

   {% if solr_required == True %}solr{% endif %}

   {% if redis_required == True %}redis{% endif %}

   {% if memcached_required == True %}memcached{% endif %}

   {% if install_vsftpd == True %}vsftpd{% endif %}

   backup

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

