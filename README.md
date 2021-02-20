# local-image-search
Reverse image search and image comparisons for local environments.

## Functions (work in progress)

Search specific directory for one image; findImage(imageName, dir)

Return multiple images that meet a certain threshold of similarity; findManyImages(imageName, dir)

Compare two images and return percent; compare(imageName, imageName)

Compare all images and return an array of the most similar images by percent; compareAll(imageName, dir)

Find copies of images in directory findCopies(dir)
