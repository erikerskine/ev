A simple Drupal module to provide a quick way of displaying any entity using a given view mode.

Usage:
- Enable the module
- Visit http://localhost/ev/{entity-type}/{entity-id}/{view-mode}

Example: to see node 5 displayed as a teaser:
- http://localhost/ev/node/5/teaser

Example: to see user 1 displayed in full:
- http://localhost/ev/user/1/full

__Important note__

This module is designed to help with theming, and __should not be enabled on a production site__.
It doesn't honour any permissions to do with entity access - any user (including anonymous users)
can view any entity.

