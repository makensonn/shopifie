# shopifyy

Shopifyy is a custom Shopify theme developed and maintained by Makenson to enhance the e-commerce experience. This repository contains the codebase for a range of Shopify stores, including products, collections, and drops, with a focus on custom HTML, CSS, and JavaScript integrations. It also incorporates the Shopify Liquid templating language to build dynamic and responsive e-commerce solutions.

#Clickable moving header 

<style>
video {
  width: 100%;
  height: auto;
  display: block;
  margin: 0 auto;
}
</style>

<a href="https://thousandmen.co/collections/all">
  <video muted autoplay playsinline loop>
    <source src="/media/cc0-videos/flower.mp4" type="video/mp4">
    <source src="https://cdn.shopify.com/videos/c/o/v/8fdd763940734076af72c7794e08401f.mp4" type="video/mp4">
  </video>
</a>


 ------------------------------------------------------------------------------------------------------------------
 
#SHOPIFY MOVING HEADER
<style>
video {
width: 100%;
height: auto;
display: block;
margin: 0 auto;
}
</style>
<video muted autoplay playsinline loop>
    <source src="/media/cc0-videos/flower.mp4"
                  type="video/mp4">
    <source src="https://cdn.shopify.com/videos/c/o/v/6108904efb5a4e9ebbabfd333d2ee518.mp4"
                  type="video/mp4">
</video>

--------------------------------------------------------------------------------------------------------------------
#Custom Sale from nav

nav a[href="/collections/sale"], 
nav a[href^="/fr/collections/sale"], 
nav a[href^="/es/collections/sale"] {
  color: green !important; 
  font-weight: bold; 
  text-transform: uppercase; 
  text-decoration: none; 
  transition: color 0.3s ease;
} 
nav a[href="/collections/sale"]:hover, 
nav a[href^="/fr/collections/sale"]:hover, 
nav a[href^="/es/collections/sale"]:hover { 
  color: red !important; 
}
