# thumbnail-classifier
A classifier which will determine the predicted views of a video based on a newly submitted thumbnail image, given the historical thumbnails and views of a channel.

## Overall Skeleton
- Connect to Youtube API to get a channel's historical thumbnails and view counts over the last 30 days
- Store this data
- Train a model on the thumbnail & view count data
- Ability to submit new images, update the model training on new videos and view counts