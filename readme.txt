Homophone Categorization Demo (Van Orden, Johnston & Hale, 1988)

Classroom demo of the categorization task in Van Orden, G. C., Johnston, J. C.,
& Hale, B. L. (1988). Word identification in reading proceeds from spelling to
sound to meaning. Journal of Experimental Psychology: Learning, Memory, and
Cognition, 14(3), 371-386. https://doi.org/10.1037/0278-7393.14.3.371

Where it lives
- This project: index.html, the source copy of the demo.
- Website copy: dpu/public_html/js/vanOrdenDemo.html in the githubWebPages
  repository (public URL once synced: https://condor.depaul.edu/dallbrit/js/vanOrdenDemo.html)
- Linked from two pages in that repository:
    dpu/public_html/js/index.html
    dpu/public_html/tools.html  ("Javascript apps and web pages" list)

Making changes
index.html in this project is the source. Edit it here, then copy it to
githubWebPages as js/vanOrdenDemo.html. The website copy has a cleaned-up
header (title in <head>, standard viewport and base styles, as in the other
demos' copies), so redo that when copying rather than copying the file as is.
Never edit the website copy directly. If the demo is also published as a
claude.ai artifact, republish index.html to that artifact after changes.

The other classroom demos are in the same place
The js folder of githubWebPages (dpu/public_html/js/) also holds the other
JavaScript demos, each linked from js/index.html and tools.html: serial
position, Sternberg memory scanning, stimulus suffix effect, Stroop, the
DRM word list memory demo, and the Seidenberg & McClelland (1989) network
demos. Put any new demo there and link it from both pages the same way.
Commit and push from githubWebPages, then run dpu/sync-condor.sh to put it
on condor.
