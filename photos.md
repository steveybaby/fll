---
layout: default
title: Photos
---

# Photo Gallery

Here are some of my favorite photos. You can organize them by categories or just display them chronologically.

## Sample Photos

To add photos, simply upload them to an `images` folder and reference them like this:

<!-- Example photo layout - replace with your actual photos -->
<div class="photo-gallery">
    <div class="photo">
        <img src="{{ '/images/sample-photo-1.jpg' | relative_url }}" alt="Description">
        <p>Photo description or caption</p>
    </div>
    
    <div class="photo">
        <img src="{{ '/images/sample-photo-2.jpg' | relative_url }}" alt="Description">
        <p>Another photo caption</p>
    </div>
</div>

## How to Add Photos

1. Create an `images` folder in your site root
2. Upload your photos to the `images` folder
3. Add them to this page using the HTML structure above
4. Or create separate gallery pages for different categories

You can also organize photos by creating separate pages like:
- `travel-photos.md`
- `nature-photos.md`
- `family-photos.md`