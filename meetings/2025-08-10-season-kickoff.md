---
layout: default
title: "Season Kickoff Meeting - August 10, 2025"
date: 2025-08-10
---

# Season Kickoff Meeting
**Date:** August 10, 2025  
**FIRST LEGO League UNEARTHED™ Season**

## Meeting Agenda

### ✅ Watch the Videos
- ✅ [Season Reveal Video](https://youtu.be/exWkcUBS0j8?si=iBuccvzflOIHoSUw)
- ✅ [Season Welcome Video](https://youtu.be/PlJ51XUoP-Q)

### ✅ Assemble the Challenges ([link](#model-building-assignments))
- ✅ Set up the competition field - see assignments below
- ✅ Place mission models according to [setup guide](https://firstinspires.blob.core.windows.net/fll/challenge/2025-26/fll-challenge-unearthed-field-setup-reference-guide.pdf)


---

## Model Building Assignments
Each team member is responsible for building specific models:

- [Model 1](https://firstinspires.blob.core.windows.net/fll/challenge/2025-26/fll-challenge-unearthed-bi-book-1-enus.pdf) - **Asher**
- [Model 2](https://firstinspires.blob.core.windows.net/fll/challenge/2025-26/fll-challenge-unearthed-bi-book-2-enus.pdf) - **Jasper**
- [Model 3](https://firstinspires.blob.core.windows.net/fll/challenge/2025-26/fll-challenge-unearthed-bi-book-3-enus.pdf) - **Ethan**
- [Model 4](https://firstinspires.blob.core.windows.net/fll/challenge/2025-26/fll-challenge-unearthed-bi-book-4-enus.pdf) - **Kai**
- [Model 5](https://firstinspires.blob.core.windows.net/fll/challenge/2025-26/fll-challenge-unearthed-bi-book-5-enus.pdf) - **Jeremiah**
- [Model 6](https://firstinspires.blob.core.windows.net/fll/challenge/2025-26/fll-challenge-unearthed-bi-book-6-enus.pdf) - **Luca**
- [Model 7](https://firstinspires.blob.core.windows.net/fll/challenge/2025-26/fll-challenge-unearthed-bi-book-7-enus.pdf) - **Asher**
- [Model 8](https://firstinspires.blob.core.windows.net/fll/challenge/2025-26/fll-challenge-unearthed-bi-book-8-enus.pdf) - **Jasper**
- [Model 9](https://firstinspires.blob.core.windows.net/fll/challenge/2025-26/fll-challenge-unearthed-bi-book-9-enus.pdf) - **Ethan**
- [Model 10](https://firstinspires.blob.core.windows.net/fll/challenge/2025-26/fll-challenge-unearthed-bi-book-10-enus.pdf) - **Kai**
- [Model 11](https://firstinspires.blob.core.windows.net/fll/challenge/2025-26/fll-challenge-unearthed-bi-book-11-enus.pdf) - **Jeremiah**
- [Model 12](https://firstinspires.blob.core.windows.net/fll/challenge/2025-26/fll-challenge-unearthed-bi-book-12-enus.pdf) - **Luca**
- [Model 13](https://firstinspires.blob.core.windows.net/fll/challenge/2025-26/fll-challenge-unearthed-bi-book-13-enus.pdf) - **Asher**

## Meeting Notes

### What We Accomplished

* We watched the [FLL launch video](https://youtu.be/exWkcUBS0j8?si=iBuccvzflOIHoSUw)
* We watched the [season welcome video](https://youtu.be/PlJ51XUoP-Q)
* We opened up the lego sets and built them

### First Core Values

**Teamwork**
- The team worked individually but then helped each other on building the models

**Innovation**
- The team persevered to build all the models, even though some were quite tricky

---

## Meeting Photos

<div class="photo-gallery" id="gallery-2025-08-10">
  <!-- Photos will be automatically loaded here -->
  <div style="grid-column: 1/-1; text-align: center; padding: 40px; color: #666; font-style: italic;">
    Add photos to <code>assets/images/meetings/2025-08-10/</code> folder and refresh the page
  </div>
</div>

<!-- Lightbox Modal -->
<div id="lightbox" class="lightbox">
  <span class="close">&times;</span>
  <img class="lightbox-content" id="lightbox-img">
  <a class="prev">&#10094;</a>
  <a class="next">&#10095;</a>
</div>

<script>
// Photo gallery functionality
let currentImageIndex = 0;
let images = [];

// Initialize gallery when page loads
document.addEventListener('DOMContentLoaded', function() {
    loadGalleryImages();
});

function loadGalleryImages() {
    const gallery = document.getElementById('gallery-2025-08-10');
    const meetingPath = '{{ "/assets/images/meetings/2025-08-10/" | relative_url }}';
    
    // Common image extensions
    const imageExtensions = ['jpg', 'jpeg', 'png', 'gif', 'webp'];
    
    // You'll need to manually add your images here for now
    // In a more advanced setup, you could use Jekyll to automatically scan the directory
    const imageList = [
        'IMG_3851.jpeg',
        'IMG_3853.jpeg', 
        'IMG_3854.JPG',
        'IMG_3855.JPG',
        'IMG_3856.JPG',
        'IMG_3857.JPG',
        'IMG_3858.JPG',
        'IMG_3859.JPG',
        'IMG_3861.jpeg',
        'IMG_3862.jpeg',
        'IMG_3863.jpeg',
        'IMG_3865.jpeg',
        'IMG_3866.jpeg',
        'IMG_3867.jpeg',
        'IMG_3868.jpeg',
        'IMG_3869.jpeg',
        'IMG_3870.jpeg',
        'IMG_3871.jpeg',
        'IMG_3872.jpeg',
        'IMG_3873.jpeg',
        'IMG_3874.jpeg',
        'IMG_3875.jpeg',
        'IMG_3876.jpeg',
        'IMG_3877.jpeg',
        'IMG_3878.jpeg'
    ];
    
    if (imageList.length === 0) {
        return; // Keep the placeholder message
    }
    
    // Clear placeholder
    gallery.innerHTML = '';
    
    // Add images to gallery
    imageList.forEach((filename, index) => {
        const img = document.createElement('img');
        img.src = meetingPath + filename;
        img.alt = `Meeting photo ${index + 1}`;
        img.onclick = () => openLightbox(index);
        gallery.appendChild(img);
        images.push(meetingPath + filename);
    });
}

function openLightbox(index) {
    currentImageIndex = index;
    const lightbox = document.getElementById('lightbox');
    const lightboxImg = document.getElementById('lightbox-img');
    
    lightboxImg.src = images[currentImageIndex];
    lightbox.style.display = 'block';
}

function closeLightbox() {
    document.getElementById('lightbox').style.display = 'none';
}

function changeImage(direction) {
    currentImageIndex += direction;
    
    if (currentImageIndex >= images.length) {
        currentImageIndex = 0;
    } else if (currentImageIndex < 0) {
        currentImageIndex = images.length - 1;
    }
    
    document.getElementById('lightbox-img').src = images[currentImageIndex];
}

// Event listeners
document.querySelector('.close').onclick = closeLightbox;
document.querySelector('.prev').onclick = () => changeImage(-1);
document.querySelector('.next').onclick = () => changeImage(1);

// Close lightbox when clicking outside the image
document.getElementById('lightbox').onclick = function(event) {
    if (event.target === this) {
        closeLightbox();
    }
};

// Keyboard navigation
document.addEventListener('keydown', function(event) {
    if (document.getElementById('lightbox').style.display === 'block') {
        switch(event.key) {
            case 'Escape':
                closeLightbox();
                break;
            case 'ArrowLeft':
                changeImage(-1);
                break;
            case 'ArrowRight':
                changeImage(1);
                break;
        }
    }
});
</script>