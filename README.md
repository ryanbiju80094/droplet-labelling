# BSA droplet labelling

A small web page for hand-labelling BSA droplet microscope images into seven morphology
categories, plus *unsure / don't include*. No install, no login, no server — open the link
and start.

## For the labeller

**Please use Google Chrome.** Chrome can save your work straight into a file on your
own computer, which means it cannot be lost. Other browsers fall back to storing it
inside the browser, which is less safe.

1. Open the link.
2. Type your name, click **Choose save file**, and save `bsa-droplet-labels.json`
   somewhere easy to find, like your Desktop.
3. Label the images. Press **1**–**8**; it moves on by itself.
4. Stop whenever you like — just close the tab. Every answer was already written to
   that file. To carry on, open the link again and click **Continue where I left off**.
5. When you're finished, email the `bsa-droplet-labels.json` file back. You can send it
   part-way through too, as often as you like.

The **Review** tab shows everything you've filed, grouped by category, and lets you
move images between categories if you change your mind. The **Summary** tab shows how
many you have in each category and has the download buttons.

Target: at least **400 images in each of the seven real categories** (Unsure / don't include
has no target).

## For whoever is collecting the results

`bsa-droplet-labels.json` is the full project state and can be reopened in the page to
resume. The Summary tab also exports a CSV, one row per labelled image, keyed by
`pool_idx` (the row index in `bsa_droplet_crops.h5`).

## Publishing

Push this folder to a GitHub repo, then Settings → Pages → Source: `main`, folder
`/ (root)`. Nothing here needs configuring and there is no build step.
