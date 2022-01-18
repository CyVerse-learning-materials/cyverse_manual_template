[![!CyVerse Learning Center](https://github.com/cyverse-learning-materials/cyverse_manual_template/raw/main/assets/cyverse_learning.png "CyVerse Learning Center"){ width="400" }](https://learning.cyverse.org)

[![!Learning Home](https://github.com/cyverse-learning-materials/cyverse_manual_template/raw/main/assets/homeicon.png "Home"){ width="25" }](https://learning.cyverse.org) [Learning Center Home](http://learning.cyverse.org/)

STYLE TIPS - DELETE THIS PAGE BEFORE PUBLISHING
===============================================

> ::: {.tip}
> ::: {.admonition-title}
> Tip
> :::
>
> Check the code (.rst) source to see how these examples are written in
> restructured text.
> :::

Many of the examples Writing your documentation using sample data
-----------------------------------------------------------------

Where possible, you want write documentation instructions to be general
enough for users can follow along with their own data. To help do this,
you can use the **sample data admonition** to intersperse sample
data-specific instructions into your generic instructions.

To do this, start your documentation with a description and where
possible, a citation of the data:

> ::: {.admonition}
> Sample data
>
> **How to use provided sample data**
>
> In this guide, we will use an RNA-Seq dataset (*\"Zika infected
> hNPCs\"*). This experiment compared human neuroprogenetor cells
> (hNPCs) infected with the Zika virus to non-infected hNPCs. You can
> read more about the experimental conditions and methods
> [here](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0175744).
> Where appropriate, a note (in this orange colored background) in the
> instructions will indicate which options to select to make use of this
> provided dataset.
>
> **Sample data citation**: Yi L, Pimentel H, Pachter L (2017) Zika
> infection of neural progenitor cells perturbs transcription in
> neurodevelopmental pathways. PLOS ONE 12(4): e0175744.
> [10.1371/journal.pone.0175744](https://doi.org/10.1371/journal.pone.0175744)
> :::

Then, as you have instructions, intersperse the sample data ..
admonition

> 1.  First, enter the cutoff value for your dataset
>
>     > ::: {.admonition}
>     > Sample data
>     >
>     > *\"Zika infected hNPCs\"* dataset:
>     >
>     > Enter **30**
>     > :::
>
> 2.  Continue with next step\...

Other admonitions
-----------------

There are several admonitions you can use, but tip and warning are the
most common for our documentation.

> ::: {.tip}
> ::: {.admonition-title}
> Tip
> :::
>
> If you don\'t see a desired species/genome [contact
> us](https://dnasubway.cyverse.org/feedback.html) to have it added
> :::
>
> ::: {.warning}
> ::: {.admonition-title}
> Warning
> :::
>
> When naming your samples and conditions, avoid spaces and special
> characters (e.g. !\#\$%\^&/, etc.). Also be sure to be consistent with
> spelling.
> :::

Buttons and keyboard combinations
---------------------------------

Where it adds clarity you can use this text to add buttons:

> 1.  Click `&Cancel`{.interpreted-text role="guilabel"} to continue
> 2.  Press `&Control`{.interpreted-text role="guilabel"} +
>     `&P`{.interpreted-text role="guilabel"} to print your result
> 3.  Fix the link in [custom\_url.txt]{.title-ref} to use this button
>     to launch a quicklaunch link in the DE (the embed HTML the DE
>     generates may not render properly in RTD)

Detail expand questions
-----------------------

You can have questions by using [.. admonition:: Question]{.title-ref}
and [.. admonition:: Answer]{.title-ref}. Just make sure you pay
attention to spacing as below.

> ::: {.admonition}
> Question
>
> 1.  Test your reader\'s knowledge with a question
>
> > ::: {.admonition}
> > Answer
> >
> > Give them an answer
> > :::
>
> 2.  Test your reader\'s knowledge with a question
>
> > ::: {.admonition}
> > Answer
> >
> > Give them an answer
> > :::
> :::

Embed video
-----------

You can embed responsive YouTube videos:

> <div class="video-container">
> <iframe width="560" height="315" align="center"
> src="https://www.youtube.com/embed/XLBpway_jG8" frameborder="0"
> allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
> allowfullscreen></iframe>
> </div>

URLs/Links
----------

Have hyperlinks open in a new tab to avoid pushing the reader off the
documentation page. Always use substitutions. Best practice is to define
your substitutions in the **cyverse\_rst\_defined\_substitutions.txt**
file in this repo for easy future updating.

Bad link \...

[bad google](https://www.google.com/)

Good link \...

Even better link (because it is defined in a separate file)

Images
------

Images should only be used when necessary.

Choose an image size that works for your page:

> ![Too big kitten](./img/kitten_no_border.png)

Better size:

> ![Right-size kitten](./img/kitten_no_border.png){width="400px"
> height="350px"}

Images should have a 1px black border:

> ![Right-size kitten w border](./img/kitten_w_border.png){width="400px"
> height="350px"}


