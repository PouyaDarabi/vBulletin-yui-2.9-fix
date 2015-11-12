# vBulletin-yui-2.9-fix

[Exploit](http://yuilibrary.com/support/20131111-vulnerability/)

This is a patched version of YUI 2.9.0 uploader.swf as used by vBulletin 4.x for managing multiple file uploads.

An exploit was found in the flash uploader (uploader.swf) file supplied with vBulletin 4.x. This file is part of the Yahoo YUI 2 Library which is end of life and Yahoo have stated that they will not be fixing it. Yahoo recommends that the file is removed as the flash uploader has been deprecated.

vBulletin's recommended fix is to replace the file with an empty file of the same name. If you do this, however, and rely solely on the Ajax uploader you will not be able to select multiple files without further modifications.

This modification is a recompiled version of uploader.swf with the above exploit fixed. An additional potential exploit has also been fixed by disabling a parameter not used by vBulletin.


How To Patch:

Download uploader.swf and replace your existing file here:

<forum_root>/clientscript/yui/uploader/assets/uploader.swf


