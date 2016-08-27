---
layout:     post
title:      "Multiple Galleries"
subtitle:   "A post with multiple galleries arranged with ISOTOPE"
date:       2015-11-23 12:00:00
author:     "MADness"
header-img: "assets/owner/blog/header/post-bg-01.jpg"
thumbnail: /assets/owner/blog/thumbs/thumb01.png
tags: [tag-name-one, tag-name-two]
category: [cat03]
comments: false
share: false
gallery1: 
  - image_path: /assets/owner/blog/galleries/g01/bg1.jpg
    image-caption: IMAGE TITLE
    image-copyright: © MADness
  - image_path: /assets/owner/blog/galleries/g01/bg2.jpg
    image-caption: IMAGE TITLE
    image-copyright: © MADness
  - image_path: /assets/owner/blog/galleries/g01/bg3.jpg
    image-caption: IMAGE TITLE
    image-copyright: © MADness 
gallery2: 
  - image_path: /assets/owner/blog/galleries/g02/bg1.jpg
    image-caption: IMAGE TITLE
    image-copyright: © MADness
  - image_path: /assets/owner/blog/galleries/g02/bg2.jpg
    image-caption: IMAGE TITLE
    image-copyright: © MADness
  - image_path: /assets/owner/blog/galleries/g02/bg3.jpg
    image-caption: IMAGE TITLE
    image-copyright: © MADness 
---

<p> Content of your post HERE </p>

<p> Add as many paragraphs amongst your galleries as you want. </p>


           {%comment%} Gallery {%endcomment%}
			
{% include subgallery.html id="gallery1" %}

<!-- end of GALLERY __ -->

<p> Add as many galleries as you want, including as many photos as you want. Simply edit the <b>FRONT MATTER</b> of the post, adding the corresponding <b>path</b>, <b>caption</b> and <b>copyright</b> info for each one of your photos. </p>

           {%comment%} Gallery {%endcomment%}
			
{% include subgallery.html id="gallery2" %}

<!-- end of GALLERY __ -->

		

###### Image Source: [UNSPLASH](https://unsplash.com/photos/j0g8taxHZa0)