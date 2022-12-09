# Web-Drawing-Interface-Test

This is a simple drawing interface using the canvas and inline Javascript within an HTML document to experiment with and test the following:

1. OpenAi's GPT-3 Codex model capabilities around frontend/UI creation
2. Practice and reinforce recent Javascript studies
3. Test potential frontend mechanics for future NFT executions

In the script comments, you can get an approximate sense of the prompt I provided to Codex as it inserts comments on its own for each instruction step asked of it.  I say approximate since in reality, this is the AI model's own interpretation of my prompt instructions, regurgitated and trimmed at times.  Unfortunately, I thought I had saved the initial prompt copy somewhere for reference, but I haven't been able to locate it.  If I do, I will provide it for anyone who is interested.

After testing the initial mechanics of the code, I started to add small bug fixes, feature additions, and improvements without the aid of the AI model. These changes included the clear button allowing users to reset the canvas and draw a new image as well as visibility logic applied to the date URL so that its container appears only when the save button has been pressed while disappearing again if the user clears the canvas.  Implemented various other *very* simple design/styling adjustments.

As this is just a capabilities test, the whole thing is still very understandably rough, unoptimized, and unrefined.  I plan to continue noodling on the interface as my schedule allows to evolve it, piecemeal, into a more sophisticated and polished product.  Will most likely refactor the javascript to utilize SVG XML to produce the user's GFX output as vectors rather than the rasterized Canvas.

The script includes a function to "save" the image as a base64 data URL.  In the future, this output can be passed as a function argument for an NFT contract's mint function.
