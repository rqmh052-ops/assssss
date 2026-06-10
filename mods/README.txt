MODS FORMAT
- Place each mod in its own folder under /mods/<id>/
- Inside each mod folder, keep:
  <id>.html
  <id>.png
  <id>.json
- Inside the mod JSON, use paths relative to that mod folder:
  page: "car.html"
  image: "car.png"
  Do not prefix paths with "mods/" inside the manifest.
- In mods/index.json, reference manifests relative to /mods/:
  "car/car.json"
