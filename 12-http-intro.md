# Using HTTP

## Modifying your Image Selector component

Modify the Image Selector component you developed previously, to retrieve its list of images from a server.

1. Create the list of images as a JSON document. I suggest also adding a name for each image. You might need to modify the URL for your own needs:

        [
          {
            "id": 4179,
            "url": "Acorn_916006_128px.png",
            "name": "Acorn"
          },
          {
            "id": 2612,
            "url": "Moon_with_stars_6563eb_128px.png",
            "name": "Moon"
          },
          {
            "id": 3495,
            "url": "Mushroom_940c4e_128px.png",
            "name": "Mushroom"
          },
          {
            "id": 1217,
            "url": "Tree_0b7843_128px.png",
            "name": "Tree"
          }
        ]

2. Retrieve this list from the server.
3. Render each image using this list. Ensure that if you change the size of the list, the rendered list length changes accordingly.

