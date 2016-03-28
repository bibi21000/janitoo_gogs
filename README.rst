.. image:: https://travis-ci.org/bibi21000/janitoo_nginx.svg?branch=master
    :target: https://travis-ci.org/bibi21000/janitoo_nginx
    :alt: Travis status

========================
Welcome to janitoo_nginx
========================

We must install a recent stable version of nginx.

This is the job of this module. It installs packages for Debian, Ubuntu and Raspdebian using method listed here : http://nginx.org/en/linux_packages.html#stable

Configuration
=============

Websockets are listen on all addresses on port 9001. This is not secure.

We must use https://www.nginx.com/blog/websocket-nginx/ in production.

mqtt is on 1883.

