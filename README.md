# Miui Camera for AOSP roms ###

- ### What is this ? ### 

  This is MIUI camera that can be prebuilt to your ROM.

- ### How to use ###

  Include this in your device makefile : 

  ```  $(call inherit-product, vendor/xiaomi/miuicamera/config.mk) ```

  Make sure to build any one of the cam packages mentioned [here](https://github.com/AtomicXZ/vendor_xiaomi_miuicamera/blob/f7c1a86f440e8cbc79bf5259cb16655e0ace2988/Android.bp#L6).

  Continue your build.
