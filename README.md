# ehouse-test

1. workflow:
    - first I downloaded the down zip and uploaded it to git in a new repo, so i can connect it to shopify and keep a version controlling environment.
    - given that it is a test I did not create a specific branch for this development
    - identify repeating elements to build snippets and avoid code repetition




## code and genral decisions:

    - use section.settings.menu.links to let the merchant set its own menu in the editor created in the navigation inside the admin (all links are  redirecting to all collections, but are easily set from the admin => navigation)
    - use clamp for responsive font-size
    - create a button snippet that can be reused latter in other sections
    - add page-width class to avoid over stretch
    - create separated files dor each section css
    - reuse banner section using schema selector and unique class to create the vacay this way section and avoid code repetition
    - add checks to reinforce 2 blocks creation
    - modified two cards align to center, the original one align to left looka weird and brakes the page harmony


## What would you discuss with a designer through the process?

    - banenr images pixelating from the root figma file, provide better images please.

## What was challenging / what wasn’t?

    - To be honest, I didn’t find anything overchallenging. The only part that required a bit more thought was making sure the code stayed clean and reusable — for example, setting up sections in a way that they could be reused and display differently without repeating code. That took some consideration.