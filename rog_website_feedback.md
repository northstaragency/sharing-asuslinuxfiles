General
-------
The top bar is not consistent across pages:
- Logo gets replace by text
- The top menu is not the same on all pages (and 'Models' is mostly missing)

The footer is not consistent across pages:
- I feel the footer at /rog-product-hub.html is the better one
  - add gitlab link


/index.html
-----------
Genral feeling: there is too much going on. I feel that this page would be better, if it had less content. (right now it kinda feels like it tries to emulate a one-page website, while being the home page of a multi-page website).

- The 'Balanced' box is confusing; it would be better to show a screenshot here.

- Buttons: why those two? 'get control center' is an obvious and valid choice, why 'catelog'? I think 'learn more' (link to: rog-product-hub.html) would be better.

- info div: nice.
  where does the info come from?
  - if 'supported models' and 'weekly download' are real info -> great
  - if 'want to have' -> remove for now.
  
- 'what you get' is hidden beneath the fold -> reduce spacing?
  - each of the 3 boxes as a 'try: ...' link; remove those links, the don't add anything, while at the same time offering the visitor a tertiary naviation option that detracts from a clear site navigation.

- 'control at your fingertips'
  1st box: confusing, with toggles that don't do anything, but serve as an example -> replace with screenshot? or remove entirely.
  2nd (row of) boxes: first two boxes talk about features of the control center, last box talks about the process. Don't mix those two, replace last box, or remove section altogether.

- 'Install in under 5 minutes'
  Let's not make any hard claims. rename into 'quick install'
  Only Arch (and family) is supported. As it is presented now, it looks like all 4 options are supported. 
  
  Maybe just remove this block?

- 'Quick Start Playbooks'
  This section adds a lot of noise. From my understanding, installing ROG control center gives you all those options, so there is no need to make separate playbook blocks for each of those, especially not on the homepage.
  
  My advice: remove this section?


/rog-product-hub.html
---------------------

Generally a strong page; keep as is : )


/rog-install-complete.html
--------------------------

Not bad, needs only minor changes.

Most importantly, Fedora/Ubunta/Debian/Mint/OpenSUSE are NOT SUPPORTED. This needs to be made super clear.
The steps presented for Arch/CachyOS/EndeavourOS/Garuda are not the same for each distro. With CachyOS for example, you can skip more than half the steps. each step needs to have a clear box indicating for which distro their are applicable.

- 'What's Next?' section
  'see supported laptops'... eeh, this needs to be _above_ the installation instructions!

- 'Frequently Asked Questions' section
  move this section to the top of the page, _above_ the install instruction.


/rog-model-page.html
--------------------

Generally a good and useful page.

However, the top-menu is now replaced by the in-page pagination. Move the pagination downward, below the model cards.


/rog-playbooks-page.html
------------------------

This is the most confusing page.

Why confusing? these are all options that describe what you can do with the ROG control center. I would expect users are able to navigate the options in the Rog control center themselves, or otherwise will look for help on a specific toggle/slider/feature. 

My advice would be to either remove this whole page, or rework it completely into a documentation page, where each toggle/slider/option/feature in the ROG control center is listed and described.


/rog-community-page.html
------------------------

Generally a good page.


/rog-legal-privacy.html
-----------------------

I'm not a lawyer.


/rog_roadmap_page.html
----------------------

Hmmm... This is open source software. Let's not advertise hard dates, because they will inevitably result in disapointments somewhere down the road.
I would say remove this page entirely, and rely on the tools/functionality of gitlab to manage this part of the project.


/rog_docs_page.html
-------------------

Wait, what? Why is this hidden in a footer link?!
This is a great format!

Replace the structure in /rog-install-complete.html by this one!!

