# Create Your Own Web Virtual Reality

<a href="https://github.com/MaksumRifai/digitaltalent/blob/master/dts-preview.png"><img src="https://raw.githubusercontent.com/MaksumRifai/digitaltalent/master/dts-preview.png"></a>

# Virtual Reality
I used A-Frame, A-Frame Is A web framework for building virtual reality experiences, A-Frame handles the 3D and WebVR boilerplate required to get running across platforms including mobile, desktop, Vive, and Rift.

# 3D Model
You can download and use 3D models or object from anywhere or create your own with Blender. For this repo, I created my own model based on DTS Kominfo Logo with MagicaVoxel, you can watch tutorial on my youtube channel here:

- [10 Menit Membuat Logo 3D (Digital Talent Scholarship)](https://www.youtube.com/watch?v=0GfNYFcDjMU&t=6s)
- [Membuat rumah dengan MagicaVoxel](https://www.youtube.com/watch?v=nbfeWj46R3c)
- [Tutorial Blender 3D Basic : View, Navigation, Transformation](https://www.youtube.com/watch?v=tEAuDC7SjsQ&t=33s)

<a href="https://www.youtube.com/watch?v=0GfNYFcDjMU&t=6s"><img src="https://i3.ytimg.com/vi/0GfNYFcDjMU/hqdefault.jpg"></a>

# Live and Preview
## Preview
<a href="https://github.com/MaksumRifai/digitaltalent/blob/master/dts-preview.gif"><img src="https://raw.githubusercontent.com/MaksumRifai/digitaltalent/master/dts-preview.gif"></a>
## Live
- https://digitaltalent.netlify.app
- https://maksumrifai.github.io/digitaltalent/

# How to use this template
## Clonning
Run the following command to clone this template to your local directory:
```
$ git clone https://github.com/MaksumRifai/digitaltalent.git

```
## Download
Use green button above and click "Download Zip" or simply click [here](https://github.com/MaksumRifai/digitaltalent/archive/master.zip)
## Customizing

```
<!DOCTYPE html>
<html>

<head>
 <meta charset="utf-8">
 <title>Digital Talent Sholarship - VR Maksum Rifai</title>
 <meta name="description" content="Digital Talent Sholarship - A-Frame VR - Maksum Rifai">
 <!--Aframe.js Core, not the latest release but most stable for this project-->
 <script src="https://aframe.io/releases/0.9.2/aframe.min.js"></script>
 <!--Aframe environment component, you can remove it if you use custom sky and plane entity -->
 <script src="https://unpkg.com/aframe-environment-component/dist/aframe-environment-component.min.js"></script>
</head>

<body>
 <a-scene>
  <!--Load assets Object 3D, Preserve all your assets below before placing it to the scene (recommended)-->
  <a-assets>
  <!--Always Asign ID to assets item for using-->
   <a-asset-item id="dts-obj" src="/DTS.obj"></a-asset-item>
   <a-asset-item id="dts-mtl" src="/DTS.mtl"></a-asset-item>
  </a-assets>
  <!--End of assets Object-->
  <!--Using Assets Above with assets ID, add desire position/scale/rotation and simple Animation-->
  <a-entity rotation="0 45 0" scale="0.01 0.01 0.01" position="0 0 -3" obj-model="obj: #dts-obj; mtl: #dts-mtl" animation="property: rotation; to: 0 360 0; loop: true; dur: 10000"></a-entity>
  <!--Add Environtment Forest Preset, alternatively use <a-plane> and <a-sky> for custom ground and sky-->
  <a-entity environment="preset: forest; dressingAmount: 500"></a-entity>
  <!--Add Camera with custom height (3 meter), default is 1.6 (160 cm), remove line below will inject default camera-->
  <a-entity camera look-controls position="0 3 0"></a-entity>
  <!--End of scene, add everything you want to show above this line-->
 </a-scene>
</body>

</html>

```

In case you want to use your own models, simply replace the [.obj .mtl .png](https://en.m.wikipedia.org/wiki/Wavefront_.obj_file) files with yours. Don't forget to export your MagicaVoxel or Blender project properly.

For better and faster development you can use [Spck Code/Git Editor](http://play.google.com/store/apps/details?id=io.spck) for Android, I mainly use this Way.

<a href="https://github.com/MaksumRifai/360vr/blob/master/360vr.gif"><img src="https://raw.githubusercontent.com/MaksumRifai/360vr/master/360vr.gif"></a>

<br/><br/>
# References & Resources

# A-Frame Boilerplate

Web framework for building virtual reality experiences.

[Github](https://github.com/aframevr/aframe) | [Website](https://aframe.io).

Alternatively, check out the [A-Frame Starter on
glitch.com](https://glitch.com/~aframe) for a more interactive way on getting
started.

# MagicaVoxel @ephtracy

A free lightweight GPU-based voxel art editor and interactive path tracing renderer.

[Github](https://github.com/ephtracy) | [Website](https://ephtracy.github.io/) | [Demo](https://youtu.be/mfKx4j-C6nI)

## Tutorial Videos

- [Youtube: Ephtracy](https://youtu.be/d_WymsNdRBA)
- [Youtube: Aaron Robbins](https://www.youtube.com/playlist?list=PLHtmobOgsDvlikllA1MBk7pk_DWlmtR_S)
- [Youtube: Maksum Rifai](https://www.youtube.com/watch?v=0GfNYFcDjMU&t=42s)

## Articles

- [Publishing Voxel Designs from MagicaVoxel to Sketchfab](https://blog.sketchfab.com/publishing-voxel-designs-from-magicavoxel-to-sketchfab/)
- [Building with MagicaVoxel and export to A-Frame (WebVR framework)](https://aframe.io/docs/0.3.0/guides/building-with-magicavoxel.html)
- [Script for animating MagicaVoxel rendering](http://drinkdecaf.com/magicavoxel_animate)

# Digital Talent Scholarship (DTS) Kominfo

## Copyright Notice & Disclaimer

All product (DTS) and company/entity names (Kominfo) are trademarks™ or registered® trademarks of their respective holders. Use of them does not imply any affiliation with or endorsement by them.
Please refer to DTS [official website](https://digitalent.kominfo.go.id) for more Information.

### Support Me
<a href="https://www.paypal.me/maksumrifai"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSRU16oC9ndfwmD5a14Df0X7B96ummOHmQGsg&usqp=CAU" width="200"></a>
<a href="https://invoice.xendit.co/donation/Dukungan"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcROR5VQJr0XTxLh-kmhGyyyQA0i8ISLTxQRcg&usqp=CAU" width="200"></a>
<a href="https://github.com/desainerhub"><img src="https://raw.githubusercontent.com/MaksumRifai/360vr/master/learn.png" width="200"></a>
<a href="https://github.com/Bekasi-Dev-Community"><img src="https://raw.githubusercontent.com/Bekasi-Dev-Community/bekasidev/master/assets/img/brand/bekasidev-stiker.png" width="200"></a>
