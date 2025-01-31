# esp32-asyncwebserver-fileupload-example

This is hopefully a simple example to demonstrate how to upload a file to an ESP32 using the AsyncWebServer, saving the files on to SPIFFS/FATFS(Fat/exFat) and having a simple upload progress bar displaced.

There are various instructions around the place, but they were all confusing and it took a long time to figure out what was needed, I hope these examples help someone.

## Example 1 - Single Webpage, File Listing, Simple Upload
- single webpage
- file listing button
- file upload button
- SPIFFS

Example-02 is more complete and offers a better user experience, with this example there is no progress of file upload after clicking the upload button.

<p align="center">
  <img src="https://raw.githubusercontent.com/rtek1000/esp32-asyncwebserver-fileupload-example/master/example-01/images/example-01-image-01.png" width="200">
</p>

---

## Example 2 - Single Webpage, Authentication, File Management, Upload with Progress Bar
- web page authentication
- single webpage
- file listing button
- file download button
- file delete button
- file upload button
- reboot esp32 button
- all done on a single web page that updates webpage elements using javascript
- SPIFFS

<p align="center">
  <img src="https://raw.githubusercontent.com/rtek1000/esp32-asyncwebserver-fileupload-example/master/example-02/images/example-02-image-01.png" width="200">
  <img src="https://raw.githubusercontent.com/rtek1000/esp32-asyncwebserver-fileupload-example/master/example-02/images/example-02-image-02.png" width="200">
  <img src="https://raw.githubusercontent.com/rtek1000/esp32-asyncwebserver-fileupload-example/master/example-02/images/example-02-image-03.png" width="200">
  <img src="https://raw.githubusercontent.com/rtek1000/esp32-asyncwebserver-fileupload-example/master/example-02/images/example-02-image-04.png" width="200">
</p>

---

## Example 3 - Single Webpage, File Listing, Simple Upload with Progress Bar
- single webpage
- file listing button
- file upload button
- progress of file upload after clicking the upload button
- HTML code in page.h file
- FatFS (see images) more info [here](https://mischianti.org/esp32-integrated-ffat-fat-exfat-filesystem-6/)

<p align="center">
    <img src="https://raw.githubusercontent.com/rtek1000/esp32-asyncwebserver-fileupload-example/master/example-03/images/example-03-image-01.png" width="200">
    <img src="https://raw.githubusercontent.com/rtek1000/esp32-asyncwebserver-fileupload-example/master/example-03/images/example-03-image-02.png" width="200">
    <img src="https://raw.githubusercontent.com/rtek1000/esp32-asyncwebserver-fileupload-example/master/example-03/images/example-03-image-03.png" width="200">
</p>

---

## Example 4 - Single Webpage, Authentication, File Management, Upload with Progress Bar
(Same as Example 2, but FatFS)

- web page authentication
- single webpage
- file listing button
- file download button
- file delete button
- file upload button
- reboot esp32 button
- all done on a single web page that updates webpage elements using javascript
- FatFS (more info [here](https://mischianti.org/esp32-integrated-ffat-fat-exfat-filesystem-6/))

<p align="center">
  <img src="https://raw.githubusercontent.com/rtek1000/esp32-asyncwebserver-fileupload-example/master/example-02/images/example-02-image-01.png" width="200">
  <img src="https://raw.githubusercontent.com/rtek1000/esp32-asyncwebserver-fileupload-example/master/example-02/images/example-02-image-02.png" width="200">
  <img src="https://raw.githubusercontent.com/rtek1000/esp32-asyncwebserver-fileupload-example/master/example-02/images/example-02-image-03.png" width="200">
  <img src="https://raw.githubusercontent.com/rtek1000/esp32-asyncwebserver-fileupload-example/master/example-02/images/example-02-image-04.png" width="200">
</p>
