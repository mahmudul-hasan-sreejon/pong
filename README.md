Pong
====

A basic game of Pong made using [Kivy](https://kivy.org/#home) framework.

# Instructions

## Working environment installation

1. Download the Kivy / Buildozer VM from [here](http://txzone.net/files/torrents/kivy-buildozer-vm-2.0.zip).

2. Extract the file and remember the location of the extracted directory.

3. Download the version of VirtualBox for your machine from [here](https://www.virtualbox.org/wiki/Downloads) and install it.

4. Start VirtualBox, click on “File”, “Import Appliance”.

5. Select the extracted directory, file should be named “Buildozer VM.ovf”

6. Start the Virtual machine and click on the “Buildozer” icon.

7. Login with the given credentials below-

<pre>
username        kivy
password        kivy
</pre>

## Building a package for android

1. Go into your application directory and execute-

<pre>
buildozer init
</pre>

2. Finally, build, deploy and run the app on your phone-

<pre>
buildozer android debug deploy run
</pre>