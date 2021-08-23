I have been experimenting with many different ways to make automatic solar quote a robust platform.

Kind of a rough overview of the timeline is:

1. Built and trained the first model using fast.ai
2. Built and trained another model in pytorch, using the same dataset as before 
3. Built another model in pytorch but aggregated another dataset containing binary labels in an attempt to seperate the roof from the rest of the image then run the previous model on the segmented image.
4. Iterated over all of the models and datasets, as well as transfer learning on pretty much every model that I came across, to try to get the accuracy as high as possible.
5. Built it into a web app using Django, bought a domain name, hosted it.
6. Took it down after a few months because I was getting no traffic and just paying for server fees
