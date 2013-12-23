Sandbox for FkrCssURLRewriteBundle
==================================

This is related to this issue https://github.com/fkrauthan/FkrCssURLRewriteBundle/issues/17

What I'm trying to do here is:

- using a Symfony standard edition (something not useful is stripped, e.g. Doctrine and SwiftMailer)
- adding a CSS with some relative paths
- adding a small change to layout to use assetic stylesheet syntax
- adding a small configuration to config.yml that uses added CSS
- using ``app/console assetic:dump`` to see if FkrCssURLRewriteBundle is working

To me, it looks like FkrCssURLRewriteBundle **doesn't work**. I hope to be wrong.