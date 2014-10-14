wp-hsGenerateGallery
====================

Wordpress Plugin - Generates Image Gallery from Folder

Contains two functions:

+createThumbnail() - Can be used alone
+hs_displayGallery() - Uses function above and outputs a list of thumbnails. Example:

```
<ul class="hs-generate-gallery">
  <li><img src="image.jpg" alt="image" /></li>
</ul>
```


Usage:

```
createThumbnail($filename, $path_to_image_directory, $path_to_thumbs_directory, $final_width_of_thumbnail)
hs_displayGallery($url)
```
