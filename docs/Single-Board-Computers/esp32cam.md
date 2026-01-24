# Help with your ESP32-CAM
Here's a few things that might be able to remedy problems you might be having with your ESP32-CAM.

These tips should solve the majority of problems!

## 1. Manually adjusting the lens focus
The ESP32‑CAM ships with a tiny adjustable lens. It’s almost always set incorrectly from the factory.

* Gently twist the lens clockwise or anticlockwise.
* Do it in very small increments.
* Use a live stream preview so you can see the focus change in real time.

This alone often transforms the image.

## 2. Check the lens for dust, fingerprints, or residue
These lenses attract smudges easily.

* Clean with a microfiber cloth.
* Avoid liquids unless absolutely necessary.

## 3. Ensure the subject isn’t too close
The stock lens has a fixed focal range.  If you need macro shots, you’ll need a different lens.

* Anything closer than ~20–30 cm tends to blur.

## 4. Improve lighting
Low light forces the sensor to increase exposure, which introduces blur and noise.

* Add more ambient light.
* Avoid pointing the camera at bright light sources (they cause glare and washout).

## 5. Check your power supply
The ESP32‑CAM is very sensitive to voltage drops.

* Use a stable 5V supply capable of at least 1A.
* Weak power can cause unstable sensor behaviour, including blurry or noisy frames.

## 6. Adjust camera settings in software
If you’re using the Arduino CameraWebServer example or similar, tweak:

* framesize (e.g., FRAMESIZE_SVGA or FRAMESIZE_VGA)
* brightness / contrast
* sharpness
* AEC / AGC (auto exposure / auto gain)
* denoise settings

Sometimes the defaults are overly soft.

## 7. Make sure the lens module is firmly seated
A loose lens mount or sensor board can cause:

* vibration blur
* misalignment
* inconsistent focus

Press gently to ensure everything is snug.

## Still having problems?
If you're still having problems after all the above steps, then do please [reach out to Hobby Stuff](https://hobbystuff.co.uk/pages/contact) to see how we can work to best resolve the situation.