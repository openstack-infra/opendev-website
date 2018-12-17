Html is rendered from Markdown using pandoc:

  pandoc -s index.md -o www/index.html -c www/index.css --metadata pagetitle="OpenDev"
