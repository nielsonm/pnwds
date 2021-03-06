!SLIDE incremental smbullets transition=cover
#Drupal Commerce: Why it rocks.

Warning, this presentation may contain odd humor, occaisional awkward moments and lots of nerd speak.

!SLIDE transition=cover
## About me
Mike Nielson (@oswebguy)

![Headshot](../file/mike-photo.jpg)

Developer at [![OpenSourcery logo](../file/opensourcery.png)](http://opensourcery.com)

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

Simply put, Drupal commerce is an eCommerce framework that allows both seasoned Drupal devs and relative Drupal noobs to build their own eCommerce sites. Drupal Commerce was devised by Ryan Szrama (rszrama), it grew out of another framework, Ubercart, during ye olde days of Drupal 6.

!SLIDE incremental smbullets transition=cover
## What is Drupal Commerce? - cont.
Drupal Commerce is exclusively available for Drupal 7+ (More on that in a minute).

!SLIDE incremental smbullets transition=cover
# Why should ***you*** care?

Drupal Commerce has a lot of momentum.
Distro users range from rszrama's hobby cheese store [http://www.realmilkcheese.com](http://www.realmilkcheese.com) to massive multinational sites selling hundreds of different products [http://www.eurocentres.com](http://www.eurocentres.com).

!SLIDE incremental smbullets transition=cover
## Why should ***you*** care?  - cont.
It's the fastest growing eCommerce distro, and has been for sometime. So let's get on the Drupal Commerce Train
![monorail cat](../file/monorailcat.jpg)

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
### Rules
### Views
### Entities

!SLIDE incremental smbullets transition=cover
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
  * The best way I can think of defining entities for old Drupal farts like me is to treat them like nodes, because they basically are.  Better said, nodes are entities in D7, as are vocabularies, blocks, terms, users and even (gasp) fields.

!SLIDE incremental smbullets transition=cover
## Entities cont.
  * They're PHP objects in D7 that can be fielded, they have CRUD methods.  Entitities are so crucial to Drupal Commerce in that Commerce creates several entitiy types, like product, line item, payment, and sale(?).

!SLIDE incremental smbullets transition=cover
## Entities cont.
  * Having entities allows Commerce to have things that act like nodes, but don't have any of the extra functionality, things like published statuses, or comment settings.
  * It also means that you can more fully use Object Oriented principles to increase the reusibility.
  * Who doesn't love OOP?!? :)

.notes TOC-slide
!SLIDE smbullets transition=cover
## What we'll cover today - Checking in.
### <s>What is Drupal Commerce</s>
### <s>Why should you care</s>
### <s>Why is commerce so powerful?</s>
### Payment methods
### Customization
### Setting up a store
### Questions & Answers

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
  Adding your own payment method, adding steps to the checkout, or custom shipping method.

  Most of these require custom code or rules which can be exported via features.
  An excellent module for adding extra steps to the checkout process is [Commerce extra panes](http://drupal.org/project/commerce_extra_panes),
  it's maintained by Pedro Cambra (pcambra) one of the major contributors to Commerce core and Commerce contrib.

  As stated previously, it's fairly straightforward to setup a [custom payment method](Adding a payment method link).


!SLIDE incremental smbullets  transition=cover
##Setting up a store.
D7 Commerce kickstart - since D8 isn't out yet.

!SLIDE incremental smbullets transitition
#Questions?  Thanks!

D.O. / IRC nielsonm - @oswebguy
