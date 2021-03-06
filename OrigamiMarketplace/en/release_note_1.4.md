# Highlights

* New payment provider : HiPay
* Use Horizon as queue management system replacing supervisord
* New Configuration on backoffice to hide/show features
* New CSV feed management with better error handling
* New authentication system
* Multi user group connection on front office
* Blade templating system in mail notifications
* Images bank system
* New ticketing display between customer & seller
* New Webhook system


# Details

## Authentication : 
* Feat : New authentication system, which can be extended by customers SSO
    
## Bank Accounts :
* Fix : fix 404 on some users on back account registration
  		
## Categories : 
* Fix : fix internal error on product position

## Dashboard : 
* Feat : Dashboard is now user centric, not user group centric
* Feat : Sellers and customers have now a default dashboard
     
## Event system :
* Feat : new recurrence field
* Feat : new log system to manage the event fired
  
## Feed system :
* Feat : New CSV feed management
* Fix : Better error handling fot CSV feed

## Images : 
* Feat : Images bank system
          
## KYC : 
* Fix : Fix KYC upload problem which occurs randomly on KYC Uploading
  
## Miscellaneous :
* Fix : Use the user locale to display date on backoffice
* Feat : new "become a seller" button
    
## Modules (Hipay) :
* Feat : New payment provider
* Feat : Can pay by credit-card & SDD
      
## Modules (Mangopay) :
* Fix : Fix bad request on user creation when the user does not supply its birthday

## Modules (Boxtal) :
* Feat : Use the push URL to fetch a package status
* Fix : Fix label generation for european delivery

## Notifications :
* Fix : Fix timezone management on emails
* Feat : You can now use blade templating system on notifcations
* Fix : Fix internal error on random notifications
* Feat : Different template using the carrier for notification
* Feat : Log for the notifications

## Orders :
* Feat : In case of relay delivery, display the relay informations instead of shipping address
* Fix : Fix random multiple payment on order seller
* Feat : Enhance communication between seller & customers
* Fix : Fix shipping label download
* Feat : New filters : customer
* Fix : Fix customer order list, bug on warehouse dispatch orders
* Feat : display all event for an order
 
## Payment Reports : 
* Fix : fix computation on order from the warehouse dispatch

## Products :
* Feat : Get the connector URL from the product
* Feat : New "Handling fees" field on product offer
* Fix : Enhance the products images upload
* Feat : Add a new filter 'enabled' for the seller
* Fix : fix bug on variant deleting
        
## Reviews :
* Fix : Fix review system with new user provider system
  
## Shipping Cart Software : 
* Fix : Better cron system to fetch modification on the Origami API
* Fix : Fix product variant image on the front system
* Fix : Better display on the seller ToS on the front office
* Feat : Rework the authentication system between the office & the API => Log in the API before SCS System to take care of the SSO
* Fix : fix duplication errors between SCS & API
    
## Shipping :
* Feat : Enhance product shipping fees configuration
* Fix : Fix update for the global shipping offer on the front system

## Taxes : 
* Fix : fix tax computing with multi taxes system
    
## Ticket :
* Feat : Add the message on the notification for a new ticket
* Feat : New ticketing display between seller & customer more like a messenger app
* Fix : Fix the order links with tickets

## Webhooks :
* Feat : New webhook system
