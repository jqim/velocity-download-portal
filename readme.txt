https://github.com/PixelsCommander/Download-File-JS


Do not forget to set Content-disposition headers in order to work properly in IE and FF.

Easiest way to configure headers via Apache is to set Header set Content-Disposition "attachment" for files you want to be downloaded.

So .htaccess can look like:

<FilesMatch "\.(zip|rar)$">
    Header set Content-Disposition attachment
</FilesMatch>

http://pixelscommander.com/polygon/downloadjs/#.VnAxc7fhAUE

