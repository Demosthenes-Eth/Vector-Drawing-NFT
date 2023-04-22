# Vector-Drawing-NFT

This project is heavily influenced by the javascript driven canvas app I made with the aid of OpenAI's scripting model. You will be able to see many similarities in the layout, though with improvements.

As the SVG file format is web native and resolution independent, I wanted to try building a new illustration app that allows users to create vector illustrations as opposed to raster drawings. To make things simpler, I opted for a pixel art style which utilizes filled squares as opposed to paths, although I do intend to continue experimenting with future iterations capable of drawing true paths as well.

My other goal was to make the entire app self-contained with as few (if any) dependencies as possible. To this end, all of the drawing functionality is included as in-line Javascript within the SVG element itself.

Finally, the end goal for the app is to serve as an intermediate image URI for a pixel art NFT collection. Users who mint an NFT from the collection will initially see the drawing app as the media for their token ID, allowing them to draw their own art inside of the app's canvas. Then by pressing the lock art button on the interface, they will be able to lock in their art and replace the image URI in the smart contract with the base64 Data URI for their own vector art.
