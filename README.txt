Html is rendered from Markdown using pandoc:

  pandoc -s index.md -o index.html -c index.css --metadata pagetitle="OpenDev"
