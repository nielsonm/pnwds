!SLIDE incremental smbullets transition=cover
#Drupal Commerce: Why it rocks.

Warning, this presentation may contain odd humor, occaisional awkward moments and lots of nerd speak.

.notes TOC-slide
!SLIDE smbullets transition=cover
## What we'll cover today.
### What is Drupal Commerce
### Why should you care
### Why is commerce so powerful?
### Payment methods
### Customization
### Setting up a store
### Questions & Answers


!SLIDE incremental smbullets transition=cover
# What is Drupal Commerce?

Simply put, Drupal commerce is an eCommerce framework that allows both seasoned Drupal devs and relative Drupal noobs to build their own eCommerce sites. Drupal Commerce was devised by Ryan Szrama (rszrama), it grew out of another framework Ubercart, during ye olde days of Drupal 6.  Drupal Commerce is exclusively available for Drupal 7+.
!SLIDE incremental smbullets transition=cover
# Why should ***you*** care?

It's the fastest growing eCommerce distro, and has been for sometime.  Drupal Commerce has a lot of momentum.  Distro users range from rszrama's hobby cheese store http://www.realmilkcheese.com to massive multinational sites selling hundreds of different products http://www.eurocentres.com.

.notes TOC-slide
!SLIDE smbullets transition=cover
## What we'll cover today - Checking in.
### <s>What is Drupal Commerce</s>
### <s>Why should you care</s>
### Why is commerce so powerful?
### Payment methods
### Customization
### Setting up a store
### Questions & Answers

!SLIDE incremental smbullets transition=cover
# Why is Commerce so powerful?

## Rules - 30 second intro
 * Rules has been a Drupal Contrib project since 2008, with D6.
 * It's a framework basically allows site builders to add functionality to their site.
   * (e.g. If a node of a certain type is published, notify the site editor of the new node, turn on comments,  unpublish the node, etc.).

!SLIDE incremental smbullets transition=cover
## Views - Yeah, it's going into core.
  * It's been part of Drupal contrib since Drupal 4 and been essertial to pretty much every site I've built since then.

!SLIDE incremental smbullets transition=cover

## Entities
  * It's already in core, Entity API makes it better.
  * Entities are an odd beast, they're new in D7, but they are the lynchpin of Drupal Commerce.
  * The best way I can think of defining entities for old Drupal farts like me is to treat them like nodes, because they basically are.  Better said, nodes are entities in D7, as are vocabularies, terms, users and even (gasp) fields.
  * They're PHP objects in D7 that can be fielded, they have CRUD methods.  Entitities are so crucial to Drupal Commerce in that Commerce creates several entitiy types, like product, line item, payment, and sale(?).
  * Having entities allows Commerce to have things that act like nodes, but don't have any of the extra functionality, things like published statuses, or comment settings.
  *It also means that you can more fully use Object Oriented principles to increase the reusibility.

!SLIDE incremental smbullets  transition=cover
## Yeah, but does it come with `<insert payment method here>`?

 * Short answer, probably.
 * Long answer, Drupal Commerce has well over 19 payment methods listed on dc.org.
 * Creating a payment is straightforward.  Seems like every week, there's at least 4-5 new Commerce payment method modules that support some new payment framework.
 * Even crazy ones like C.O.D. and Bill Me Later.

.notes TOC-slide
!SLIDE smbullets transition=cover
## What we'll cover today - Checking in.
### <s>What is Drupal Commerce</s>
### <s>Why should you care</s>
### <s>Why is commerce so powerful?</s>
### <s>Payment methods</s>
### Customization
### Setting up a store
### Questions & Answers


!SLIDE incremental smbullets  transition=cover
##How to customize it.

Customizing your commerce install can take many forms, such as:
  Adding your own payment method.
  Adding steps to the checkout.

!SLIDE incremental smbullets  transition=cover
##Setting up a store.

!SLIDE incremental smbullets transitition
#Questions?

