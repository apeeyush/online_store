README
=======

This repository contains a sample rails app I built while learning Ruby on Rails.

This application implements an online store, with a catalog, cart, and orders.

It is divided into two main sections:

* The buyer's side of the application manages the catalog, cart, 
  and checkout. It is implementation spans in four models and associated
  controllers and views: Cart, LineItem, Order, and Product.  Additionally,
  there is a StoreController for the store front itself, and a
  SessionsController to manage sessions.

* Only administrators can access stuff in the seller's side
  (product maintenance and order fulfillment).  This is implemented by the
  SessionsController, is enforced by the ApplicationController#authorize
  method, and assisted by the Users and Carts resources.

=== Author

 * Peeyush Agarwal

=== Warranty

This code is provided for educational purposes only, and comes with 
absolutely no warranty. It should not be used in live applications.


Licence
=======

               DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                       Version 2, December 2004
    
    Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>
    
    Everyone is permitted to copy and distribute verbatim or modified
    copies of this license document, and changing it is allowed as long
    as the name is changed.
    
               DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
      TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION
    
     0. You just DO WHAT THE FUCK YOU WANT TO.
