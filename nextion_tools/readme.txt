From Simhub dev:

It seems that some nextion screens are now bundled with firmwares not allowing anymore to use older nextion editor versions. Unfortunately those screens can't be used with simhub directly.

As a workaround you can create the nextion file using simhub included nextion editor then
Make a copy of the HMI file and open it with the latest nextion editor found on the manfucturer website. Upload it as you would usually do, using the newer nextion editor (for ttl adapter) or nextion uploader (for Arduino pro micro)

So, for older Nextion firmware:

1 - Use legacy Nextion Editor to create template and HMI for Simhub.
2 - Upload template to Nextion using the legacy editor.
3 - Open HMI in Simhub and customize.

For newer Nextion displays:

1 - Use legacy Nextion Editor to create template and HMI for Simhub.
2 - Copy project from legacy editor and open it in new editor.
3 - Upload template using new editor.
4 - Open HMI in Simhub and customize.
