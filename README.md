# Droplet labelling

A small web page for hand-labelling droplet microscope images into six morphology
categories. No install, no login, no server — open the link and start.

## For the labeller

**Please use Google Chrome.** Chrome can save your work straight into a file on your
own computer, which means it cannot be lost. Other browsers fall back to storing it
inside the browser, which is less safe.

1. Open the link.
2. Type your name, click **Choose save file**, and save `droplet-labels.json`
   somewhere easy to find, like your Desktop.
3. Label the images. Press **1**–**7**; it moves on by itself.
4. Stop whenever you like — just close the tab. Every answer was already written to
   that file. To carry on, open the link again and click **Continue where I left off**.
5. When you're finished, email the `droplet-labels.json` file back. You can send it
   part-way through too, as often as you like.

The **Review** tab shows everything you've filed, grouped by category, and lets you
move images between categories if you change your mind. The **Summary** tab shows how
many you have in each category and has the download buttons.

Target: at least **200 images in each of the six real categories** (Unsure has no
target). That works out at roughly 1,300–1,800 images in total.

## For whoever is collecting the results

`droplet-labels.json` is the full project state and can be reopened in the page to
resume. The Summary tab also exports a CSV, one row per labelled image, keyed by
`pool_idx`.

## Publishing

Push this folder to a GitHub repo, then Settings → Pages → Source: `main`, folder
`/ (root)`. The site appears at `https://<user>.github.io/<repo>/` within a minute or
two. Nothing here needs configuring and there is no build step.
