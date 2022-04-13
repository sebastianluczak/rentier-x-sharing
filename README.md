# PHP - Rentier

### What is PHP Rentier

**Rentier** is set of `interfaces` aimed for PHP developers to accelerate creation of X-sharing model in your app.

As it's only a domain wrapper around set of interfaces it's up to you how you implement your business logic.

### How can I use PHP Rentier
As long as you stay within those interfaces your app will be consistent with common logic of services such as:
- cleaning and/or maintenance duties on-site or off-site
- ordering certain online services (i.e. workshop sessions) and managing attendees
- multi-vendor e-commerce solutions of any kinds

Everywhere, where you're managing shared resources as services and has to deal with things like planning and management - that's where PHP Rentier kicks in.

X-sharing solutions nad app ideas can be represented by common objects in common design flows. 

Rentier tries to capture that objects, represents them as PHP interfaces and allows full extension with other supportive tools in PHP.

### How to use
Using this model allows to kickstart your x-sharing site with custom code in minutes, not hours.

As `PHP Rentier` is framework-independent and you can use it everywhere using Composer package.

```shell
composer require sebastianluczak/rentier-x-sharing
```

All the interfaces resides in `Rentier` namespace.
You can use provided factories from `Rentier\Factory\*Interface` to see some entry-points for your implementation.

Rentier package is based on years of experience and hundreds of apps.

And it's free - MIT Licensed.